---
layout: docs_0.9.0
active: angularjs
title: "Loading"
header_sub_title: "Loading overlay and indicator"
---

Available in:
<div class="label label-danger">Ionic-Angular 0.9.0</div>
<div class="label label-primary">Ionic 0.9.0</div>


Loading
===

The Loading is an overlay that can be used to indicate activity while blocking user interaction.


<img src="http://ionicframework.com.s3.amazonaws.com/docs/controllers/loading.gif" alt="Loading" style="border: 1px solid #eee">

## Ionic-Angular Usage

To trigger Loading in your code, use the `Loading` service in your angular controllers or directives:

```javascript

angular.module('test', ['ionic'])

.controller(function($scope, ['Loading', Loading) {

  // Trigger the loading indicator
  $scope.show = function() {

    // Show the loading overlay and text
    $scope.loading = Loading.show({

      $scope.loadingIndicator = Loading.show({

          // The text to display in the loading indicator
          content: 'Loading',

          // The animation to use
          animation: 'fade-in',

          // Will a dark overlay or backdrop cover the entire view
          showBackdrop: true,

          // The maximum width of the loading indicator
          // Text will be wrapped if longer than maxWidth
          maxWidth: 200,

          // The delay in showing the indicator
          showDelay: 500
      });
    });
  };

  // Hide the loading indicator
  $scope.hide = function(){
    $scope.loading.hide();
  }
}]);
```