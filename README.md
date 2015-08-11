# spa-router
Client side router for Single Page Application (SPA)

Router uses history API so even tho it is client side
router (doesn't do page reload) doesn't use hashes (#)
but slashes(/).

This project is working but it is still in development.
When it becames stable version will changed to 1. 

## Instalation

### CLI

```
npm install push-router
```

### package.json

```
"push-router": "x.y.z"
```

## Usage

### Getting module

```
var Router = require("push-router");
```

### Adding route

```
Router.addRoute(route, callback)
```

### Adding default route

```
Router.addDefaultRoute(callback)
```