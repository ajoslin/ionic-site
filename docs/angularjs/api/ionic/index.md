---
layout: docs_0.9.0
active: javascript
title: "ionic"
header_sub_title: "Module in module ext"
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
        <td><a href="/docs/angularjs/api/ionic/directive/ionHeaderBar">ionHeaderBar</a></td>
        <td><p>While Ionic provides simple Header and Footer bars that can be created through
HTML and CSS alone, Header bars specifically can be extended in order to
provide dynamic layout features such as auto-title centering and animation.
They are also used by the Views and Navigation Controller to animate a title
on navigation and toggle a back button.
*
The main header bar feature provide is auto title centering.
In this situation, the title text will center itself until either the
left or right button content is too wide for the label to center.
In that case, it will slide left or right until it can fit.
You can also align the title left for a more Android-friendly header.</p>
</td>
      </tr>
      
      <tr>
        <td><a href="/docs/angularjs/api/ionic/directive/ionContent">ionContent</a></td>
        <td><p>The ionContent directive provides an easy to use content area that can be configured to use
Ionic&#39;s custom Scroll View, or the built in overflow scorlling of the browser.</p>
</td>
      </tr>
      
      <tr>
        <td><a href="/docs/angularjs/api/ionic/directive/ionInfiniteScroll">ionInfiniteScroll</a></td>
        <td><p>The ionInfiniteScroll directive, when placed inside of <a href="/docs/angularjs/api/ionic/directive/ionContent">ionContent</a>, allows you to call a function whenever the user gets to the bottom of the page or near the bottom of the page.</p>
</td>
      </tr>
      
    </table>
  </div>
  
</div>




