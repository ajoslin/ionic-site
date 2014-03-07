---
layout: docs_0.9.0
active: javascript
title: "ion-header-bar"
header_sub_title: "Directive in module ionic"
doc: "ionHeaderBar"
---

<div class="pull-right">
  <a href='http://github.com/driftyco/ionic/edit/master/{$ doc.relativePath $}' class='improve-docs'>Improve this doc</a>
  <a href='http://github.com/driftyco/ionic/tree/master/js/ext/angular/src/directive/ionicBar.js#L16' class='view-source'>
    View Source
  </a>
</div>




## ion-header-bar



While Ionic provides simple Header and Footer bars that can be created through
HTML and CSS alone, Header bars specifically can be extended in order to
provide dynamic layout features such as auto-title centering and animation.
They are also used by the Views and Navigation Controller to animate a title
on navigation and toggle a back button.
*
The main header bar feature provide is auto title centering.
In this situation, the title text will center itself until either the
left or right button content is too wide for the label to center.
In that case, it will slide left or right until it can fit.
You can also align the title left for a more Android-friendly header.

Using two-way data binding, the header bar will automatically
readjust the heading title alignment when the title or buttons change.








  
## Usage
  

```html
<ion-header-bar
 title="{{myTitle}}"
 left-buttons="leftButtons"
 right-buttons="rightButtons"
 type="bar-positive"
 align-title="center">
</ion-header-bar>
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
        title
        
        
      </td>
      <td>
        string
      </td>
      <td>
        <p>The title use on the headerBar.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        leftButtons
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        expression
      </td>
      <td>
        <p>Point to an array of buttons to put on the left of the bar.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        rightButtons
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        expression
      </td>
      <td>
        <p>Point to an array of buttons to put on the right of the bar.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        type
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        string
      </td>
      <td>
        <p>The type of the bar, for example &#39;bar-positive&#39;.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        align
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        string
      </td>
      <td>
        <p>Where to align the title. &#39;left&#39;, &#39;right&#39;, or &#39;center&#39;.  Defaults to &#39;center&#39;.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>
</section>
  





