# Atatus-SPA

[Atatus](https://www.atatus.com) Real User Monitoring and error tracking agent for single page applications (SPA).

[Signup for Atatus](https://www.atatus.com/signup).

## Getting Started

### Install

**Using yarn**

```
yarn add atatus-spa
```

**Using npm**

```
npm install atatus-spa --save
```

### Usage

In your web page:

```html
<script type="text/javascript" src="/PATH_TO_ATATUS/atatus-spa.min.js"></script>
<script>
  atatus.config('YOUR_API_KEY').install();
</script>
```

For more advanced options, refer [our documentation](https://docs.atatus.com/docs/browser-monitoring/customize-agent.html).


### CDN

Atatus is also available from our content delivery network:

```html
<script type="text/javascript" src="https://dmc1acwvwny3.cloudfront.net/atatus-spa.js"></script>
<script>
  atatus.config('YOUR_API_KEY').install();
</script>
```

### CommonJS

To use Atatus with CommonJS imports:

```javascript
var atatus = require('atatus-spa');
atatus.config('YOUR_API_KEY').install();
```

### ES2015 (ES6)

To use Atatus with ES2015 (ES6) imports:

```javascript
import * as atatus from 'atatus-spa';
atatus.config('YOUR_API_KEY').install();
```
