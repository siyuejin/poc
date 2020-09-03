# POC - Angular & Angular Universal 

## Build Setup

```bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at http://localhost:4200/
$ ng serve

# build for production and launch server
$ npm run build:ssr && npm run serve:ssr

# generate static project
$ npm run build:ssr
```

## Runing in Docker

To build Docker image:

```bash
docker build -t poc-app .
```

and run it:

```bash
docker run -p 80:80 poc-app
```

Navigate to http://localhost in order to see the containerized application.

