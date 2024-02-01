
## Quickstart With Tina

```
$ npm install && npm run tina
```


This will install dependencies and open the website in your browser.

Visit the CMS at [http://localhost:3000/admin](http://localhost:3000/admin) to start editing.

## About

This website is built using [Docusaurus 2](https://docusaurus.io/) and [TinaCMS](https://tina.io/) and [redocusorus](https://redocusaurus.vercel.app/)


### Installation

```
$ npm install
```


### Local Development

```
$ npm run tina
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server. Go to the [Tina Admin](http://localhost:3000/admin) to start editing.


### Routing 

I have taken an sample openapi file , present in openapi directory.
To route to api documentation , open

```
http://localhost:3000/api/
```

To route to Tina cms editor

```
http://localhost:3000/admin/
```


### Build

```
$ npm run build
```

Or

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

To deploy to production and support editing on your live website (at **your-domain.com/admin**), you can follow the steps from [Tina's docs](https://tina.io/docs/forestry/migrate/#deploy-tina-to-your-site).
