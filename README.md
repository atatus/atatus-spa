# Atatus-SPA

[Atatus](https://www.atatus.com) Real User Monitoring and error tracking agent for single page applications (SPA).

[Signup for Atatus](https://www.atatus.com/signup).

## Getting Started

### With NPM

Run `npm install atatus-spa --save`

### With Bower

Run `bower install atatus-spa`

## Usage

In your web page:

```html
<script type="text/javascript" src="/PATH_TO_ATATUS/atatus-spa.min.js"></script>
<script>
  atatus.config('YOUR_API_KEY').install();
</script>
```

For more advanced options, refer [our documentation](https://www.atatus.com/docs).


### CDN

Atatus is also available from our content delivery network:

```html
<script type="text/javascript" src="https://dmc1acwvwny3.cloudfront.net/atatus-spa.js"></script>
<script>
  atatus.config('YOUR_API_KEY').install();
</script>
```

### Module loaders (CommonJS)

Atatus can be loaded using a module loader like Browserify or Webpack.

```javascript
var atatus = require('atatus-spa');
atatus.config('YOUR_API_KEY').install();
```

