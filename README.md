# AjaxRequest

Minimalist AJAX request module. This module is only compatible with browsers and Node versions that support ES6 classes and promises.

# Usage

Include the module.
```javascript
// AMD
var AjaxRequest = require(['ajaxrequest']);

// CommonJS
var AjaxRequest = require('ajaxrequest');
```

Use the module.
```javascript
var ajaxRequest = new AjaxRequest(
  'GET',
  'http://www.site.com/data.json',
  true
);

ajaxRequest.send().then(function(successResponse, failResponse) {
    // Do stuff
});
```

