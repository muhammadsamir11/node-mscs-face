# node-mscs-face
A javascript wrapper for Microsoft Cognitive Services' Face API.
We are in no way affiliated to Microsoft.

## Easy to start using
This module is based off a wrapper wrote for Microsoft Cognitive Services' Face API duing a major school project.
It exposes the services provided by Face API into a set of functions that can be easily invoked in your Node.js project.

```js
// Require the module
const FaceApi = require('node-mscs-face');

// Pass in your Face API subscription key and your Face API's region to get started
var faceApi = new FaceApi('faceapi_subscription_key', 'region');
```

## Table of contents
- [Region](#region)
- [Detect](#detect)
- [Identify](#identify)
- [Add Face](#add-face)
- [Delete Face](#delete-face)
- [Create Person](#create-person)
- [Delete Person](#delete-person)
- [Train Person Group](#train-person-group)
- [Custom Implementations](#custom-implementations)
- [Things to Do](#things-to-do)

Services that are being wrapped for Face API are stated in the table of contents above, everything else is work in progress.
For Face API documentation, please refer to [Microsoft's Cognitive Services Face API References](https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395236)



