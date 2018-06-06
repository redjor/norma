# Switch
####  Like turning your lights on!

!> Redaction in Progress

```html
<div class="ka-Switch">
  <input type="checkbox" class="ka-Switch__input" id="">
  <label for="">
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