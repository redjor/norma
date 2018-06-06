# Switch
####  Like turning your lights on!

!> Redaction in Progress
<div class="demo-block">
  <div class="ka-Switch" style="width: 48px;">
    <input type="checkbox" class="ka-Switch__input" id="id">
    <label for="id">
      <span class="off-icon"></span>
      <span class="on-icon"></span>
    </label>
  </div>
</div>
```html
<div class="ka-Switch">
  <input type="checkbox" class="ka-Switch__input" id="switch">
  <label for="switch">
    <span class="off-icon"></span>
    <span class="on-icon"></span>
  </label>
</div>
```

!>The classes `.off-icon` & `.on-icon` are directly hard-coded, so you can't add content those elements. You can delete them.

***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$switchButtonSize`| 24px |
|`$switchButtonColor`| $white |
|`$switchBgColor`| $cloud |
|`$switchActiveBgColor`| $success |