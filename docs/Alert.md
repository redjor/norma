# Alert

The Alert  component is like the iOS one. It brings you a fade centered window menu with buttons. By default, the element is **hidden** and you need to add `ka-Alert__animate` to the parent element in order to make it visible with the animation.

<div class="demo-block" style="height: 280px;">
    <div class="ka-Alert__dialog" style="display: block; position: absolute;">
        <div class="ka-Alert__dialog-container">
        <!-- Title -->
        <div class="ka-Alert__dialog-title">Title</div>
        <!-- Content -->
        <div class="ka-Alert__dialog-content">
        Here is some content!        
        </div>
        <!-- Footer -->
        <div class="ka-Alert__dialog-footer">
            <!-- Add your buttons list here -->
            <button class="ka-Alert__dialog-button">Ok</button>
        </div>
        </div>
    </div>
    <div class="ka-Alert__dialog-mask" style="position: absolute;"></div>
</div>

The **mask** is triggered simply by adding `display:block` or `display: none`. The best way will be to add this mask in the DOM only when the component is active.

```html
<div class="ka-Alert__dialog">
  <div class="ka-Alert__dialog-container">
     <!-- Title -->
    <div class="ka-Alert__dialog-title"></div>
     <!-- Content -->
    <div class="ka-Alert__dialog-content"></div>
     <!-- Footer -->
    <div class="ka-Alert__dialog-footer">
        <!-- Add your buttons list here -->
        <button class="ka-Alert__dialog-button"></button>
    </div>
  </div>
</div>
```
***

## Buttons
The footer contain buttons with `ka-Alert__dialog-button` class.
```html
<button class="ka-Alert__dialog-button">Label</button>
```

##  Buttons in Row
Put `ka-Alert__dialog-footer--row` class to the dialog footer `ka-Alert__dialog-footer` in order to have the buttons in row .
```html
<div class="ka-Alert__dialog-footer ka-Alert__dialog-footer--row">Label</div>
```

##  Focused button
If you want to focus a button, add `ka-Alert__dialog-button--focus` class.
```html
<button class="ka-Alert__dialog-button ka-Alert__dialog-button--focus">Label</button>
```

***
## JS example
The following example is used in the HTML/CSS version. It could help you to understand how the component is triggered.

```js
var createAlertDialog = function(id) {
    var el = document.getElementById(id);
    el.classList.add('ka-Alert__animate');
    var mask = document.createElement('div');
    mask.className = 'ka-Alert__dialog-mask';
    mask.id = 'alert-mask'
    el.parentNode.insertBefore(mask, el);
};
var hideAlertDialog = function(id) {
    document.getElementById(id).style.display = 'none';
    var el = document.getElementById(id);
    el.classList.remove('ka-Alert__animate');
    var mask = document.getElementById('alert-mask');
    if (mask) {
        mask.parentNode.removeChild(mask);
    }
};
```

Add this code to a button to trigger the function.
```js
 onclick="createAlert(id, maskId)"
```
!> You are free to use your own function, and It's highly recommanded !

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$AlertTitleColor` | `black` |
|`$AlertContentColor` | `black` |
|`$AlertButtonHeight` | `44px` |
|`$AlertButtonColor` | `#0076ff` |
|`$AlertButtonBorderColor` | `#ddd` |
|`$AlertDialogPadding` | `8px 16px 16px` |
|`$AlertBorderRadius` | `11px` |
|`$AlertBgColor` | `white` |
|`$AlertZIndex` | `999` |