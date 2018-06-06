# Toast

!> Redaction in Progress


`.ka-Toast`

```html
<div class="ka-Toast">
  <div class="ka-Toast__message"></div>
  <button class="ka-Toast__button></button>
</div>
```

>The Toast is hidden by **default**, so you need to add `.ka-Toast__visible` to `.ka-Toast`.



***
Position
---------
`.ka-Toast--top` or `.ka-Toast--bottom`
```html
<div class="ka-Toast ka-Toast--top">
```

Colors
-------
| Color  | Classname |
| ------- |:-----------:|
|  Default  |`.ka-Toast--default`|
|  Success  |`.ka-Toast--success`|
|  Warning  |`.ka-Toast--warning`|
|  Info  |`.ka-Toast--info`| 
|  Danger |`.ka-Toast--danger`|



***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$toastBorderRadius`| 5.5px |
|`$toastMargin`| .5rem |
|`$toastPadding`| .5rem 1rem |
|`$toastBoxShadow`|  0 1rem 2rem rgba(0,0,0,.2) |
|`$toastZIndex`| 1500 |