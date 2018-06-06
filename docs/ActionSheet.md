# Action Sheet

The ActionSheet  component is like the iOS one. It brings you a bottom menu with actions list. By default, the element is **hidden** and you need to add `ka-ActionSheet__animate` to the parent element in order to make it visible with the animation.

The **mask** is triggered simply by adding `display:block` or `display: none`. The best way will be to add this mask in the DOM only when the component is active.

```html
<div class="ka-ActionSheet__mask"></div>
<div class="ka-ActionSheet">
  <!-- Add your buttons list here -->
  <button class="ka-ActionSheet__button">Label</button>
</div>
```

###  Title
You can add a title to your action sheet just after the parent.
```html
<div class="ka-ActionSheet">
  <div class="ka-ActionSheet__title">Title</div>
</div>
```

###  Destructive button
A destructive button is a button with a red label and separated from the others. 

Just add `ka-ActionSheet__button--destructive` class to the element. The way to use it, is to put this button at the end of the list.
```html
<button class="ka-ActionSheet__button ka-ActionSheet__button--destructive">Label</button>
```

***
### JS example
The following example is used in the HTML/CSS version. It could help you to understand how the component is triggered.

```js
var createActionSheetDialog = function(id, maskId) {
    var el = document.getElementById(id);
    el.classList.add('ka-ActionSheet__animate');
    document.getElementById(maskId).style.display = 'block';
};
var hideActionSheetDialog = function(id, maskId) {
    var el = document.getElementById(id);
    el.classList.remove('ka-ActionSheet__animate');
    document.getElementById(maskId).style.display = 'none';
};
```

Add this code to a button to trigger the function.
```js
 onclick="createActionSheetDialog(id, maskId)"
```
!> You are free to use your own function, and It's highly recommanded !
***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$ActionSheetButtonColor`| #0076ff |
|`$ActionSheetButtonBgColor` |rgba(255, 255, 255, 0.9) |
|`$ActionSheetBorderColor `|#D5D5D5 |
|`$ActionSheetBorderRadius` |12px |
|`$ActionSheetTitleColor`| black |