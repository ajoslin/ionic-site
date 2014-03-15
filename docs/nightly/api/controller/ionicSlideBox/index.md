---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/controller/ionicSlideBox"
group: "Other"

title: "ionicSlideBox"
header_sub_title: "Controller in module ionic"
doc: "ionicSlideBox"
docType: "controller"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/views/sliderView.js#L9'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ionicSlideBox



</h1>





Controller for the <a href="/docs/nightly/api/directive/ionSlideBox"><code>ionSlideBox</code></a> directive.










  

  
## Methods

<div id="slide"></div>
<h2>
  <code>slide(to, [speed])</code>

</h2>





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
        to
        
        
      </td>
      <td>
        
  <code>number</code>
      </td>
      <td>
        <p>The index to slide to.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        speed
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>number</code>
      </td>
      <td>
        <p>The number of milliseconds for the change to take.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>









<div id="prev"></div>
<h2>
  <code>prev()</code>

</h2>

Go to the previous slide. Wraps around if at the beginning.









<div id="next"></div>
<h2>
  <code>next()</code>

</h2>

Go to the next slide. Wraps around if at the end.









<div id="stop"></div>
<h2>
  <code>stop()</code>

</h2>

Stop sliding. The slideBox will not move again until
explicitly told to do so.









<div id="currentIndex"></div>
<h2>
  <code>currentIndex()</code>

</h2>








* Returns: 
   number The index of the current slide.




<div id="slidesCount"></div>
<h2>
  <code>slidesCount()</code>

</h2>








* Returns: 
   number The number of slides there are currently.



  
  






