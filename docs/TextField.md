# TextField
#### A home for Form controls

The Textfield component provides a container and help you to add some informations like, alerts, description and helps elements.

<div class="demo-block">
  <div class="ka-TextField">
    <input class="ka-TextInput__input" placeholder="Text">
    <label class="ka-TextInput__label">Label</label>
    <!-- if the textInput has an alert -->
    <div class="ka-TextField__message danger">alertMessage</div>
    <!-- Show the alert icon on the right side of the input -->
    <span class="ka-TextField__alert-icon">
      <i class="fa fas fa-exclamation-circle danger"></i>
    </span>
  </div>
</div>

```html
<div class="ka-TextField">
  <input class="ka-TextInput__input">
  <label class="ka-TextInput__label"></label>
  <!-- if the textInput has an alert -->
  <div class="ka-TextField__message danger">alertMessage</div>
  <!-- Show the alert icon on the right side of the input -->
  <span class="ka-TextField__alert-icon">
    <i class="fa fas fa-exclamation-circle danger"></i>
  </span>
</div>
```

### Alerts
Add the following class alerts to `ka-TextField__message` & `ka-TextField__alert-icon` to stylizing the Field.

| Alert Name | Classname |
| ------- |:-----------:|
| Info | `info` |
| Warning | `warning` |
| Danger | `danger`|
| Success | `success` |




***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
| `$textFieldBgColor`| `$white` |
| `$textFieldColor`| `$dark` |
| `$textFieldIconColor`| `$purpledark` |
| `$textFieldMessageColor`| `$white` |
| `$textFieldMessageBgColor`| `$black` |
| `$textFieldHelpBgColor`| `$cloud` |
| `$textFieldPadding`| `16px` |