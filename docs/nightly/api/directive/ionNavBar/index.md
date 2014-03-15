---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionNavBar"
group: "navigation"

title: "ion-nav-bar"
header_sub_title: "Directive in module ionic"
doc: "ionNavBar"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicNavBar.js#L174'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-nav-bar



<small>
  (controller: <a href="/docs/nightly/api/controller/ionicNavBar"><code>ionicNavBar</code></a>)
</small>

</h1>





If we have an <a href="/docs/nightly/api/directive/ionNavView"><code>ionNavView</code></a> directive, we can also create an
`<ion-nav-bar>`, which will create a topbar that updates as the application state changes.

We can add a back button by putting an <a href="/docs/nightly/api/directive/ionNavBackButton"><code>ionNavBackButton</code></a> inside.

We can add buttons depending on the currently visible view using
<a href="/docs/nightly/api/directive/ionNavButtons"><code>ionNavButtons</code></a>.








  
<h2 id="usage">Usage</h2>
  
```html
<body ng-app="starter">
  <!-- The nav bar that will be updated as we navigate -->
  <ion-nav-bar
    animation="nav-title-slide-ios7"
    type="bar-positive"></ion-nav-bar>

  <!-- where the initial view template will be rendered -->
  <ion-nav-view animation="slide-left-right"></ion-nav-view>
</body>
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
        <p>The model to assign the
<a href="/docs/nightly/api/controller/ionicNavBar">ionicNavBar controller</a> to.
Default: assigns it to $scope.navBarController.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        animation
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The animation used to transition between titles.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        type
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The className for the navbar.  For example, &#39;bar-positive&#39;.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        align
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>Where to align the title of the navbar.
Available: &#39;left&#39;, &#39;right&#39;, &#39;center&#39;. Defaults to &#39;center&#39;.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>

  

  





