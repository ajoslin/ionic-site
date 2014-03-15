---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/controller/ionicNavBar"
group: "navigation"

title: "ionicNavBar"
header_sub_title: "Controller in module ionic"
doc: "ionicNavBar"
docType: "controller"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicNavBar.js#L4'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ionicNavBar



</h1>





Controller for the <a href="/docs/nightly/api/directive/ionNavBar"><code>ionNavBar</code></a> directive.










  

  
## Methods

<div id="back"></div>
<h2>
  <code>back([event])</code>

</h2>

Goes back in the view history.



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
        event
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>DOMEvent</code>
      </td>
      <td>
        <p>The event object (eg from a tap event)</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="align"></div>
<h2>
  <code>align([direction])</code>

</h2>

Calls <a href="/docs/nightly/api/controller/ionicBar#align">ionicBar#align</a> for this navBar.



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
        direction
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The direction to the align the title text towards.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="showBackButton"></div>
<h2>
  <code>showBackButton(show)</code>

</h2>

Set whether the <a href="/docs/nightly/api/directive/ionNavBackButton"><code>ionNavBackButton</code></a> should be shown (if it exists).



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
        show
        
        
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether to show the back button.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="showBar"></div>
<h2>
  <code>showBar(show)</code>

</h2>

Set whether the <a href="/docs/nightly/api/directive/ionNavBar"><code>ionNavBar</code></a> should be shown.



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
        show
        
        
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether to show the bar.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="setTitle"></div>
<h2>
  <code>setTitle(title)</code>

</h2>

Set the title for the <a href="/docs/nightly/api/directive/ionNavBar"><code>ionNavBar</code></a>.



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
        title
        
        
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The new title to show.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="changeTitle"></div>
<h2>
  <code>changeTitle(title, direction)</code>

</h2>

Change the title, transitioning the new title in and the old one out in a given direction.



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
        title
        
        
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The new title to show.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        direction
        
        
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>The direction to transition the new title in.
Available: &#39;forward&#39;, &#39;back&#39;.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="getTitle"></div>
<h2>
  <code>getTitle()</code>

</h2>








* Returns: 
  <code>string</code> The current title of the navbar.




<div id="getPreviousTitle"></div>
<h2>
  <code>getPreviousTitle()</code>

</h2>








* Returns: 
  <code>string</code> The previous title of the navbar.



  
  






