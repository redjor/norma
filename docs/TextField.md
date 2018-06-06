# TextField

!> Redaction in Progress

```html
<div class="ka-TextField">
    <input class="ka-TextInput__input">
    <label class="ka-TextInput__label"></label>
    <!-- if the textInput has an alert -->
    <div class="ka-TextField__message">alertMessage</div>
    <!-- Show the alert icon on the right side of the input -->
    <span class="ka-TextField__alert-icon">
      <i class="fa fas"></i>
    </span>
</div>
```

Alerts
------
`.ka-TextField__message`
`.danger`

`.ka-TextField__alert-icon`
`.danger`

Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
| `$textFieldBgColor`| $white |
| `$textFieldColor`| $dark |
| `$textFieldIconColor`| $purple-dark |
| `$textFieldMessageColor`| $white |
| `$textFieldMessageBgColor`| $black |
| `$textFieldHelpBgColor`| $cloud |
| `$textFieldPadding`| 16px |