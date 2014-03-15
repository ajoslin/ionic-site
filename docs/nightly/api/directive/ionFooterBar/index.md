---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionFooterBar"
group: "Other"

title: "ion-footer-bar"
header_sub_title: "Directive in module ionic"
doc: "ionFooterBar"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicBar.js#L53'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-footer-bar



<small>
  (controller: <a href="/docs/nightly/api/controller/ionicBar"><code>ionicBar</code></a>)
</small>

</h1>





Adds a fixed footer bar below some content.

Is able to have left or right buttons, and additionally its title can be
aligned through the <a href="/docs/nightly/api/controller/ionicBar">ionicBar controller</a>.








  
<h2 id="usage">Usage</h2>
  
```html
<ion-content>
  Some content!
</ion-content>
<ion-footer-bar align-title="left">
  <div class="buttons">
    <button class="button">Left Button</button>
  </div>
  <h1 class="title">Title!</h1>
  <div class="buttons">
    <button class="button">Right Button</button>
  </div>
</ion-footer-bar>
```
  
  
<h2 id="api" style="clear:both;">API</h2>

<table class="table" style="margin:0;">
  <thead>
    <tr>
      <th>Attr</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        model
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The model to assign this footerBar&#39;s 
<a href="/docs/nightly/api/controller/ionicBar">ionicBar controller</a> to. 
Defaults to assigning to $scope.footerBarController.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        align-title
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>Where to align the title at the start.
Avaialble: &#39;left&#39;, &#39;right&#39;, or &#39;center&#39;.  Defaults to &#39;center&#39;.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>

  

  





