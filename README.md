<p align="center">
  <a href="https://pg-all.portal.azure-api.net/" target="_blank">
    <img width="280" src="/docs/.vuepress/public/momo.png" alt="MTN MoMo Logo">
  </a>
</p>



# MTN MoMo API Documentation

> The purpose of this site is to detail the design principles, objects, behaviours and error handling for the MTN Mobile Money API.

At the heart of our brand is the will to enable and support local development & transformation through technology. With that in mind, through this portal we start the journey of exposing our Mobile Money APIs to the public thus easing access for Developers and Entrepreneurs who wish to innovate. 

# Documentation

## Online 

[Online](https://mtn-momo-api-documentation.firebaseapp.com/)

## Locally

Clone the repo and change directory into it

```
git clone https://github.com/sparkplug/mtn-momo-api-documentation.git
cd mtn-momo-api-documentation
```

Make sure you have Yarn or NPM installed. You should then install `Vuepress` locally or globally

```
# install globally
yarn global add vuepress # OR npm install -g vuepress

# install as a local dependency
yarn add -D vuepress # OR npm install -D vuepress

```

You can now run it locally:

```
yarn docs:dev # OR npm run docs:dev
```

To generate static assets:

```
yarn docs:build # Or npm run docs:build
```

## License

MIT