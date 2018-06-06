# Loading
#### It won't be too long

The loading component is a spinner at the center of the window.


```html
<div class="ka-Loading">
  <div class="ka-Loading__wrapper">
    <div class="ka-Loading__spinner"></div>
  </div>
</div>
```

Transparent
----------
You can have a transparent overlay by adding `ka-Loading__transparent` class to `ka-Loading`.
```html
<div class="ka-Loading ka-Loading__transparent">
</div>
```

Caption
--------
The loader can have a caption at the bottom. So add your message in a element with `ka-Loading__caption`, just after the spinner.
```html
<div class="ka-Loading">
  <div class="ka-Loading__wrapper">
    <div class="ka-Loading__spinner"></div>
    <div class="ka-Loading__caption"></div>
  </div>
</div>
```

***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$LoadingSpinnerColor`|#ffffff |
|`$LoadingSpinnerSize`| 32px |
|`$LoadingSpinnerSpeed`| .8s |
|`$LoadingSpinnerThickness`| 8px |
|`$LoadingBorderRadius`| 5.5px |
|`$LoadingBgColor`| black |
|`$LoadingFullscreenBgColor`| rgba(black , .75) |
|`$LoadingBoxShadow`| 0 1rem 2rem rgba(0,0,0,.2) |
