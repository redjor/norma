# TextInput
#### I'll  keep the message

The TextInput component overrides the default text input with new style with `ka-TextInput` class.

<div class="demo-block">
  <div class="ka-TextInput">
    <input class="ka-TextInput__input" placeholder="Input">
    <label class="ka-TextInput__label">
      <i class="fa far fa-money-check"></i>
        Label
    </label>
  </div>
</div>

### Default
You can use the default input and add `ka-TextInput__input` to stylized it.

```html
<input class="ka-TextInput__input">
```

### Label
A label can be displayed above the input with `ka-TextInput__label` class and wrapped into `ka-TextInput` class
```html
<div class="ka-TextInput">
  <input class="ka-TextInput__input" value="Input" disabled>
  <label class="ka-TextInput__label">
      Label
  </label>
</div>
```

### Icon
An icon can be placed directly into the label element before the text.
```html
  <label class="ka-TextInput__label">
    <i class="fa far fa-money-check"></i>Label
  </label>
```
?> In this case, we use FontAwesome.

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$textInputLabelFontSize` | `12px` |
|`$textInputLabelColor` | `$darklight` |
|`$textInputBgColor` | `transparent` |
|`$textInputInputFontSize` | `1rem` |
|`$textInputInputHeight` | `16px` |
|`$textInputFocusColor` | `$purpledark` |
