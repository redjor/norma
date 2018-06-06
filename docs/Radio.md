# Radio
#### I know you can turn me on
We have hidden the native radio button and wrapped in `ka-Radio` class element in order to have full control on the new design.

<div class="demo-block">
  <div class="ka-Radio">
    <input type="radio" name="radio" id="3" class="ka-Radio__input">
    <div class="ka-Radio__container">
      <label class="ka-Radio__radio" for="3"></label>
      <label class="ka-Radio__label" for="3">Radio</label>
    </div>
    <div class="ka-Radio__description">Such a good place to add a description</div>
  </div>
</div>
You can append a description below your radio button.
```html
<div class="ka-Radio">
  <input type="radio" name="name" id="ID" class="ka-Radio__input">
  <div class="ka-Radio__container">
    <label class="ka-Radio__radio" for="ID"></label>
    <label class="ka-Radio__label" for="ID">Label</label>
  </div>
</div>
```
You can check a radio button by default by adding the checked HTML attribute to the `<input>` element.

?> Make sure the linked radio buttons have the same value for their name HTML attribute.

Description
------
You can append a description below your label. You need to add a `.ka-Radio__description` at the end of `ka-Radio`.

```html
<div class="ka-Radio">
  <div class="ka-Radio__container"></div>
  <!-- Add your description here -->
  <div class="ka-Radio__description">Your description</div>
</div>
```

***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |-----------:|
|`$radioSize:`| `24px`|
|`$radioBorderSize`| `2px`|
|`$radioLabelPaddingLeft`| `12px`|
|`$radioBgColor`| `$white`|
|`$radioBorderColor`| `$cloud`|
|`$radioActiveColor`| `$white`|
|`$radioActiveBgColor`| `$primary`|
|`$radioDescriptionColor`| `$dark-lighter`|
