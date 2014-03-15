---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/controller/ionicTabs"
group: "tab bar"

title: "ionicTabs"
header_sub_title: "Controller in module ionic"
doc: "ionicTabs"
docType: "controller"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicTabBar.js#L9'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ionicTabs



</h1>





Controller for the <a href="/docs/nightly/api/directive/ionTabs"><code>ionTabs</code></a> directive.










  

  
## Methods

<div id="selectedTabIndex"></div>
<h2>
  <code>selectedTabIndex()</code>

</h2>








* Returns: 
   `number` The index of the selected tab, or -1.




<div id="selectedTab"></div>
<h2>
  <code>selectedTab()</code>

</h2>








* Returns: 
   `ionTab` The selected tab or null if none selected.




<div id="select"></div>
<h2>
  <code>select(tabOrIndex, [shouldChangeHistory])</code>

</h2>

Select the given tab or tab index.



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
        tabOrIndex
        
        
      </td>
      <td>
        
  <code>ionTab</code>|<code>number</code>
      </td>
      <td>
        <p>A tab object or index of a tab to select</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        shouldChangeHistory
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether this selection should load this tab&#39;s view history
(if it exists) and use it, or just loading the default page. Default false.
Hint: you probably want this to be true if you have an
<a href="/docs/nightly/api/directive/ionNavView"><code>ionNavView</code></a> inside your tab.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>








  
  






