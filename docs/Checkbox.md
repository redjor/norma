# Checkbox
#### The 2-state Box

<a href="https://ibb.co/fuffLo"><img src="https://image.ibb.co/ibhufo/checkbox.png" alt="checkbox" border="0" height="64px"></a>

We have hidden the native radio button and wrapped in `.ka-Checkbox` in order to have full control on the design.

You can append a description below your checkbox.

?> Make sure to put the same ID for the input and the label

```html
<div class="ka-Checkbox">
  <input type="checkbox" name="" id="ID" class="ka-Checkbox__input">
  <div class="ka-Checkbox__container">
    <span class="ka-Checkbox__checkbox" for="ID"></span>
    <label class="ka-Checkbox__label">Label</label>
  </div>
</div>
```
You can check a checkbox button by default by adding the **checked** HTML attribute to the `<input>` element.


Description
------
You can append a description below your label. You need to add a `.ka-Checkbox__description` element at the end of `.ka-Checkbox`.

```html
<div class="ka-Checkbox">
  <div class="ka-Checkbox__container">
    <input type="checkbox" name="" id="" class="ka-Checkbox__input">
    <label class="ka-Checkbox__checkbox" for=""></label>
    <label class="ka-Checkbox__label">Label</label>
  </div>
  <div class="ka-Checkbox__description">Description</div>
</div>
```

Disabled
---------
Just add the **disabled** attribute to the input to have the whole component disabled.

***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |-----------:|
|`$checkboxSize`| 24px |
|`$checkboxBorderSize`| 2px |
|`$checkboxBorderRadius`| 2.5px |
|`$checkboxLabelPaddingLeft`|:12px |
|`$checkboxBgColor`| white |
|`$checkboxBorderColor`| black |
|`$checkboxActiveColor`| white |
|`$checkboxActiveBgColor`| black |
|`$checkboxDescriptionColor`| rgba(0,0,0,0.8) |


