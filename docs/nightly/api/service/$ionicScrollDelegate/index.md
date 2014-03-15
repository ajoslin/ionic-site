---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/service/$ionicScrollDelegate"
group: "page layout"

title: "$ionicScrollDelegate"
header_sub_title: "Service in module ionic"
doc: "$ionicScrollDelegate"
docType: "service"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/service/delegates/ionicScrollDelegate.js#L6'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  $ionicScrollDelegate



</h1>





Allows you to have some control over a scrollable area (created by an
<a href="/docs/nightly/api/directive/ionContent"><code>ionContent</code></a> or <a href="/docs/nightly/api/directive/ionScroll"><code>ionScroll</code></a>
directive).

Inject it into a controller, and its methods will send messages to the nearest scrollView and all of its children.









## Usage
```html
<ion-content ng-controller="MyController">
  <button class="button" ng-click="scrollToTop()">
    Scroll To Top
  </button>
</ion-content>
```
```js
function MyController($scope, $ionicScrollDelegate) {
  $scope.scrollToTop = function() {
    $ionicScrollDelegate.scrollTop();
  };
}
```


  

  
## Methods

<div id="scrollTop"></div>
<h2>
  <code>scrollTop([shouldAnimate])</code>

</h2>





<table class="table" style="margin:0;">
  <thead>
    <tr>
      <th>Param</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        shouldAnimate
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether the scroll should animate.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="scrollBottom"></div>
<h2>
  <code>scrollBottom([shouldAnimate])</code>

</h2>





<table class="table" style="margin:0;">
  <thead>
    <tr>
      <th>Param</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        shouldAnimate
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether the scroll should animate.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="scroll"></div>
<h2>
  <code>scroll(left, top, [shouldAnimate])</code>

</h2>





<table class="table" style="margin:0;">
  <thead>
    <tr>
      <th>Param</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        left
        
        
      </td>
      <td>
        
  <code>number</code>
      </td>
      <td>
        <p>The x-value to scroll to.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        top
        
        
      </td>
      <td>
        
  <code>number</code>
      </td>
      <td>
        <p>The y-value to scroll to.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        shouldAnimate
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether the scroll should animate.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="anchorScroll"></div>
<h2>
  <code>anchorScroll([shouldAnimate])</code>

</h2>

Tell the scrollView to scroll to the element with an id
matching window.location.hash.

If no matching element is found, it will scroll to top.



<table class="table" style="margin:0;">
  <thead>
    <tr>
      <th>Param</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        shouldAnimate
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether the scroll should animate.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="resize"></div>
<h2>
  <code>resize()</code>

</h2>

Tell the scrollView to recalculate the size of its container.








  
  






