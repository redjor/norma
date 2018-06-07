# Toast
#### Bread everywhere

The Toast component helps you to display important informations to your user. 

<div class="demo-block">
  <div class="ka-Toast ka-Toast--success" style="position: relative; display: flex; width: 100%;">
    <div class="ka-Toast__message">I'm a toast element</div>
    <button class="ka-Toast__button">Close</button>
  </div>
</div>

Use the `.ka-Toast` class element below: 

```html
<div class="ka-Toast">
  <div class="ka-Toast__message"></div>
  <button class="ka-Toast__button"></button>
</div>
```

>The Toast is hidden by **default**, so you need to add `ka-Toast__visible` to `ka-Toast`.


### Action
Add the label action into `ka-Toast__button`.

### Position
The toast can be positioned on the **top** or at the **bottom** be adding the following class:

 `.ka-Toast--top` or `.ka-Toast--bottom`
```html
<div class="ka-Toast ka-Toast--top">
```

### Colors
| Color  | Classname |
| ------- |:-----------:|
|  Default  |`.ka-Toast--default`|
|  Success  |`.ka-Toast--success`|
|  Warning  |`.ka-Toast--warning`|
|  Info  |`.ka-Toast--info`| 
|  Danger |`.ka-Toast--danger`|


### JS Example
We use the following JS function, to add/remove `ka-Toast__visible` to the element.

```js
var createToastDialog = function(id) {
    var el = document.getElementById(id);
    el.classList.add('ka-Toast__visible');

};
var hideToastDialog = function(id) {
    var el = document.getElementById(id);
    el.classList.remove('ka-Toast__visible');
};
```
!> It's highly recommanded to use your own function.

***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$toastBorderRadius`| 5.5px |
|`$toastMargin`| .5rem |
|`$toastPadding`| .5rem 1rem |
|`$toastBoxShadow`|  0 1rem 2rem rgba(0,0,0,.2) |
|`$toastZIndex`| 1500 |