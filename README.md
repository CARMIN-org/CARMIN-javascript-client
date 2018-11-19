# CARMIN-javascript-client
Javascript library to communicate with a platform through a CARMIN API

## Documentation

* This new version of the client uses the promises to manage the asynchronous calls.
* To use it
* ````javascript
  var carminClient = new CarminClient(carminURL, carminAPIKey);

  var myPromise = carminClient.listPipelines();

  myPromise.then(function (data){
      // Success function
    }, function (err){
      // Fail function
    }
  );

* [More documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) to use the promises
