---
layout: docs_0.9.0
active: javascript
title: "ion-infinite-scroll"
header_sub_title: "Directive in module ionic"
doc: "ionInfiniteScroll"
---

<div class="pull-right">
  <a href='http://github.com/driftyco/ionic/edit/master/{$ doc.relativePath $}' class='improve-docs'>Improve this doc</a>
  <a href='http://github.com/driftyco/ionic/tree/master/js/ext/angular/src/directive/ionicContent.js#L189' class='view-source'>
    View Source
  </a>
</div>




## ion-infinite-scroll



The ionInfiniteScroll directive, when placed inside of <a href="/docs/angularjs/api/ionic/directive/ionContent">ionContent</a>, allows you to call a function whenever the user gets to the bottom of the page or near the bottom of the page.

The expression you pass in for `on-scroll` is called when the user scrolls down until he is `distance` away from the bottom of the screen.








  
## Usage
  

```html
<ion-content ng-controller="MyController">
  <ion-infinite-scroll
    on-infinite="loadMore()"
    distance="1%">
  </ion-infinite-scroll>
</ion-content>
```
```js
function MyController($scope, $http) {
  $scope.items = [];
  $scope.loadMore = function() {
    $http.get('/more-items').success(function(items) {
      useItems(items);
      $scope.$broadcast('scroll.infiniteScrollComplete');
    });
  };
}
```

An easy to way to stop infinite scroll once there is no more data to load is to use angular's `ng-if` directive:

```html
<ion-infinite-scroll
  ng-if="moreDataCanBeLoaded()"
  on-infinite="loadMoreData()">
</ion-infinite-scroll>
```

  
  

## API

<table class="table">
  <thead>
    <tr>
      <th>Attributes</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        on-infinite
        
        
      </td>
      <td>
        expression
      </td>
      <td>
        <p>What to call when the scroller reaches the bottom.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        distance
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        string
      </td>
      <td>
        <p>The distance from the bottom that the scroll must reach to trigger the on-infinite expression. Default 1%.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>
</section>
  





