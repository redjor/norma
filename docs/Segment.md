# Segment
#### Sometimes, we need to be separated
The Segment component allows you to have styled buttons in a bar with only one active button at a time.

<div class="demo-block">
  <div class="ka-Segment">
    <div class="ka-Segment__item">
      <input type="radio" name="segment" class="ka-Segment__input" checked>
      <div class="ka-Segment__button">Label 1</div>
    </div>
    <div class="ka-Segment__item">
      <input type="radio" name="segment"  class="ka-Segment__input">
      <div class="ka-Segment__button">Label 2</div>
    </div>
    <div class="ka-Segment__item">
      <input type="radio" name="segment" class="ka-Segment__input">
      <div class="ka-Segment__button">Label 3</div>
    </div>
  </div>
</div>

```html
<div class="ka-Segment">
  <!-- Add Segment item for each label -->
  <div class="ka-Segment__item">
    <input type="radio" name="name" class="ka-Segment__input">
    <div class="ka-Segment__button"></div>
  </div>
</div>
```
***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$SegmentColor`| `black` |
|`$SegmentBgColor`| `transparent` |
|`$SegmentActiveColor`| `white` |
|`$SegmentActiveBgColor`| `black` |
|`$SegmentBorderRadius`| `4px` |