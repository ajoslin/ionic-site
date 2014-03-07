---
layout: docs_0.9.0
active: javascript
title: "ion-content"
header_sub_title: "Directive in module ionic"
doc: "ionContent"
---

<div class="pull-right">
  <a href='http://github.com/driftyco/ionic/edit/master/{$ doc.relativePath $}' class='improve-docs'>Improve this doc</a>
  <a href='http://github.com/driftyco/ionic/tree/master/js/ext/angular/src/directive/ionicContent.js#L19' class='view-source'>
    View Source
  </a>
</div>




## ion-content



The ionContent directive provides an easy to use content area that can be configured to use
Ionic's custom Scroll View, or the built in overflow scorlling of the browser.

While we recommend using the custom Scroll features in Ionic in most cases, sometimes (for performance reasons) only the browser's native overflow scrolling will suffice, and so we've made it easy to toggle between the Ionic scroll implementation and overflow scrolling.

You can implement pull-to-refresh with the <a href="/docs/angularjs/ionic.directive:ionRefresher">ionRefresher</a> directive, and infinite scrolling with the <a href="/docs/angularjs/api/ionic/directive/ionInfiniteScroll">ionInfiniteScroll</a> directive.








  
## Usage
  
    

  ```html
  <ion-content
    [scroll=""]
    [overflow-scroll=""]
    [padding=""]
    [has-header=""]
    [has-subheader=""]
    [has-footer=""]
    [has-bouncing=""]
    [on-refresh=""]
    [on-refresh-opening=""]
    [on-scroll=""]
    [on-scroll-complete=""]>
  ...
  </ion-content>
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
        scroll
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to allow scrolling of content.  Defaults to true.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        overflow-scroll
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to use overflow-scrolling instead of Ionic scroll.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        padding
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to add padding to the content.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        has-header
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to offset the content for a header bar.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        has-subheader
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to offset the content for a subheader bar.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        has-footer
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to offset the content for a footer bar.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        has-bouncing
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        boolean
      </td>
      <td>
        <p>Whether to allow scrolling to bounce past the edges of the content.  Defaults to true on iOS, false on Android.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        on-refresh
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        expression
      </td>
      <td>
        <p>Expression to evaluate on refresh completion.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        on-refresh-opening
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        expression
      </td>
      <td>
        <p>Expression to evaluate on refresh opening.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        on-scroll
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        expression
      </td>
      <td>
        <p>Expression to evaluate when the content is scrolled.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        on-scroll-complete
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        expression
      </td>
      <td>
        <p>Expression to evaluate when a scroll action completes.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>
</section>
  





