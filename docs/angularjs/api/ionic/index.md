---
layout: docs_0.9.0
active: javascript
title: "ionic"
header_sub_title: "ionic"
doc: "ionic"
---

<div class="pull-right">
  <a href='http://github.com/driftyco/ionic/edit/master/{$ doc.relativePath $}' class='improve-docs'>Improve this doc</a>
  <a href='http://github.com/driftyco/ionic/tree/master/js/ext/angular/src/ionicAngular.js#L6' class='view-source'>
    View Source
  </a>
</div>


<h1>
  <code>ionic</code>
</h1>

<p>Ionic main module.</p>



  <h2>Installation</h2>

  <p>First include <code>undefined</code> in your HTML:</p>

  <pre><code>    &lt;script src=&quot;angular.js&quot;&gt;&#10;    &lt;script src=&quot;&quot;&gt;</code></pre>

  <p>You can download this file from the following places:</p>
  <ul>
    <li>
      <a href="https://developers.google.com/speed/libraries/devguide#angularjs">Google CDN</a><br>
      e.g. <code>//ajax.googleapis.com/ajax/libs/angularjs/X.Y.Z/undefined</code>
    </li>
    <li>
      <a href="http://bower.io">Bower</a><br>
      e.g. <pre><code>bower install @X.Y.Z</code></pre>
    </li>
    <li>
      <a href="http://code.angularjs.org/">code.angularjs.org</a><br>
      e.g. <pre><code>&quot;//code.angularjs.org/X.Y.Z/&quot;</code></pre>
    </li>
  </ul>
  <p>where X.Y.Z is the AngularJS version you are running.</p>
  <p>Then load the module in your application by adding it as a dependent module:</p>
  <pre><code>  angular.module(&#39;app&#39;, [&#39;ionic&#39;]);</code></pre>

  <p>With that you&apos;re ready to get started!</p>


<div class="component-breakdown">
  <h2>Module Components</h2>
  
  <div>
    <h3 class="component-heading" id="directive">Directive</h3>
    <table class="definition-table">
      <tr>
        <th>Name</th>
        <th>Description</th>
      </tr>
      
      <tr>
        <td><a href="api/ionic/directive/ionContent">ionContent</a></td>
        <td><p>The ionContent directive provides an easy to use content area that can be configured to use
Ionic&#39;s custom Scroll View, or the built in overflow scorlling of the browser.</p>
</td>
      </tr>
      
      <tr>
        <td><a href="api/ionic/directive/ionInfiniteScroll">ionInfiniteScroll</a></td>
        <td><p>TODO make complete. Mention &#39;scroll.infiniteScrollComplete&#39; event
Mention using ng-if if you wish to stop loading more.</p>
</td>
      </tr>
      
    </table>
  </div>
  
</div>




