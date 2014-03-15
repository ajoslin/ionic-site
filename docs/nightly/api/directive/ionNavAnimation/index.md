---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionNavAnimation"
group: "navigation"

title: "ion-nav-animation"
header_sub_title: "Directive in module ionic"
doc: "ionNavAnimation"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicNavAnimation.js#L3'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-nav-animation


<small>
  (child of <a href="/docs/nightly/api/directive/ionNavView"><code>ionNavView</code></a>)
</small>


</h1>





When used under an <a href="/docs/nightly/api/directive/ionNavView"><code>ionNavView</code></a> and on an `<a>` element,
allows you to set the animation all clicks on that link within the navView use.








  
<h2 id="usage">Usage</h2>
  
```html
<ion-nav-view>
  <ion-view>
    <ion-content>
      <a href="#/some-page" ion-nav-animation="slide-in-up">
        Click me and #/some-page will transition in with the slide-in-up animation!
      </a>
    </ion-content>
  </ion-view>
</ion-nav-view>
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
        ion-nav-animation
        
        
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The animation to make the parent ionNavView change pages with when clicking this element.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>

  

  





