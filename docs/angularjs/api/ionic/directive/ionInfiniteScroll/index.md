---
layout: docs_0.9.0
active: javascript
title: "ion-infinite-scroll"
header_sub_title: "ionInfiniteScroll"
doc: "ionInfiniteScroll"
---

<div class="pull-right">
  <a href='http://github.com/driftyco/ionic/edit/master/{$ doc.relativePath $}' class='improve-docs'>Improve this doc</a>
  <a href='http://github.com/driftyco/ionic/tree/master/js/ext/angular/src/directive/ionicContent.js#L191' class='view-source'>
    View Source
  </a>
</div>




## ion-infinite-scroll



TODO make complete. Mention 'scroll.infiniteScrollComplete' event
Mention using ng-if if you wish to stop loading more.








  
## Usage
  
    
* as element:

  ```html
  <ion-infinite-scroll
    on-scroll=""
    [distance=""]>
  ...
  </ion-infinite-scroll>
  ```
    
  
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
        on-scroll
        
        
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
        <p>The distance from the bottom that the scroll must reach to trigger the on-scroll expression. Default 1%.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>
</section>
  





