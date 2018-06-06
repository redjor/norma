# TextInput
#### I'll  keep the message
!> Redaction in Progress

<div class="demo-block">
  <div class="ka-TextInput">
    <input class="ka-TextInput__input" placeholder="Input">
    <label class="ka-TextInput__label">
      <i class="fa far fa-money-check"></i>
        Label
    </label>
  </div>
</div>

```html
<input class="ka-TextInput__input">
```

```html
<label class="ka-TextInput__label">Label</label>
<input class="ka-TextInput__input">
```

```html
<div class="ka-TextInput">
  <input class="ka-TextInput__input" value="Input" disabled>
  <label class="ka-TextInput__label">
    <i class="fa far fa-money-check"></i>
      Label
  </label>
</div>
```

Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$textInputLabelFontSize` | 12px |
|`$textInputLabelColor` | $dark-light |
|`$textInputBgColor` | transparent |
|`$textInputInputFontSize` | 1rem |
|`$textInputInputHeight` | 16px |
|`$textInputFocusColor` | $purple-dark |
