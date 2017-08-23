# node-mscs-face
A javascript wrapper for Microsoft Cognitive Services' Face API.

## Easy to start using
This module is based off a wrapper wrote for Microsoft Cognitive Services' Face API duing a major school project.
It exposes the services provided by Face API into a set of functions that can be easily invoked in your Node.js project.

```js
// Require the module
const FaceApi = require('node-mscs-face');

// Pass in your Face API subscription key and your Face API's region to get started
var faceApi = new FaceApi('faceapi_subscription_key', 'region');
```

