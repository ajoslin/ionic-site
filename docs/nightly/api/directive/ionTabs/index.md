---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionTabs"
group: "tab bar"

title: "ion-tabs"
header_sub_title: "Directive in module ionic"
doc: "ionTabs"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicTabBar.js#L131'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-tabs



<small>
  (controller: <a href="/docs/nightly/api/controller/ionicTabs"><code>ionicTabs</code></a>)
</small>

</h1>


{% include codepen.html id="KbrzJ" %}




Powers a multi-tabbed interface with a Tab Bar and a set of "pages" that can be tabbed through.

See the <a href="/docs/nightly/api/directive/ionTab"><code>ionTab</code></a> directive's documentation for more details.








  
<h2 id="usage">Usage</h2>
  
```html
<ion-tabs tabs-type="tabs-icon-only">

  <ion-tab title="Home" icon-on="ion-ios7-filing" icon-off="ion-ios7-filing-outline">
    <!-- Tab 1 content -->
  </ion-tab>

  <ion-tab title="About" icon-on="ion-ios7-clock" icon-off="ion-ios7-clock-outline">
    <!-- Tab 2 content -->
  </ion-tab>

  <ion-tab title="Settings" icon-on="ion-ios7-gear" icon-off="ion-ios7-gear-outline">
    <!-- Tab 3 content -->
  </ion-tab>
</ion-tabs>
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
        
  <code>expression</code>
      </td>
      <td>
        <p>The model to assign this tab bar&#39;s <a href="/docs/nightly/api/controller/ionicTabs"><code>ionicTabs</code></a> controller to. By default, assigns  to $scope.tabsController.</p>

        
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
        <p>The animation to use when changing between tab pages.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        tabs-style
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The class to apply to the tabs. Defaults to &#39;tabs-positive&#39;.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        tabs-type
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>Whether to put the tabs on the top or bottom. Defaults to &#39;tabs-bottom&#39;.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>

  

  





