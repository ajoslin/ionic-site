---
layout: docs_api
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionNavBackButton"
group: "navigation"

title: "ion-nav-back-button"
header_sub_title: "Directive in module ionic"
doc: "ionNavBackButton"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/ext/angular/src/directive/ionicNavBar.js#L261'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-nav-back-button


<small>
  (child of <a href="/docs/nightly/api/directive/ionNavBar"><code>ionNavBar</code></a>)
</small>


</h1>





Creates a back button inside an <a href="/docs/nightly/api/directive/ionNavBar"><code>ionNavBar</code></a>.

Will show up when the user is able to go back in the current navigation stack.

By default, will go back when clicked.  If you wish for more advanced behavior, see the 
examples below.








  
<h2 id="usage">Usage</h2>
  
With default click action:

```html
<ion-nav-bar>
  <ion-nav-back-button class="button-icon">
    <i class="ion-arrow-left-c"></i> Back!
  </ion-nav-back-button>
</ion-nav-bar>
```

With custom click action, using <a href="/docs/nightly/api/controller/ionicNavBar">ionicNavBar controller</a>:

```html
<ion-nav-bar model="navBarController">
  <ion-nav-back-button class="button-icon"
    ng-click="canGoBack && navBarController.back()">
    <i class="ion-arrow-left-c"></i> Back
  </ion-nav-back-button>
</ion-nav-bar>
```

Displaying the previous title on the back button, again using
<a href="/docs/nightly/api/controller/ionicNavBar">ionicNavBar controller</a>.

```html
<ion-nav-bar model="navBarController">
  <ion-nav-back-button class="button button-icon ion-arrow-left-c">
    {% raw %}{{navBarController.getPreviousTitle() || 'Back'}}{% endraw %}
  </ion-nav-back-button>
</ion-nav-bar>
```
  
  

  





