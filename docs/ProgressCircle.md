# Progress Circle
#### 0 to 100 real quick
The Progress Circle component display a progression bar in a circle without JS.

<div class="demo-block">
  <div class="ka-ProgressCircle ka-ProgressCircle__progress-50" style="margin-right: 16px;">
      <div class="ka-ProgressCircle__slice">
        <div class="ka-ProgressCircle__bar">
        </div>
        <div class="ka-ProgressCircle__fill"></div>
    </div>
  </div>
    <div class="ka-ProgressCircle ka-ProgressCircle__progress-35" style="margin-right: 16px;">
      <div class="ka-ProgressCircle__slice">
        <div class="ka-ProgressCircle__bar">
        </div>
        <div class="ka-ProgressCircle__fill"></div>
    </div>
  </div>
    <div class="ka-ProgressCircle ka-ProgressCircle__progress-15" >
      <div class="ka-ProgressCircle__slice">
        <div class="ka-ProgressCircle__bar">
        </div>
        <div class="ka-ProgressCircle__fill"></div>
    </div>
  </div>
</div>

```html
<div class="ka-ProgressCircle" >
    <div class="ka-ProgressCircle__slice">
      <div class="ka-ProgressCircle__bar">
      </div>
      <div class="ka-ProgressCircle__fill"></div>
  </div>
</div>
```
Progression
-------------
In order to add the progression to the circle, you need to add `ka-ProgressCircle__progress-100` class to `ka-ProgressCircle` element.

?> Replace **`100`** by the value of the progress. It will fill the circle automaticaly.

Icons
------
You can add an icon inside the circle. You should keep `18px` width & height maximum.
```html
<div class="ka-ProgressCircle" >
  <span>
    <!-- Add your icon here -->
    <img src="/assets/icons/*.svg" height="18px" width="18px">
  </span>
  <div class="ka-ProgressCircle__slice">
    <div class="ka-ProgressCircle__bar"></div>
    <div class="ka-ProgressCircle__fill"></div>
  </div>
</div>
```
***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$ProgressCircleWidth`|` 48px` |
|`$ProgressCirclePrimaryColor`| `$purple` |
|`$ProgressCircleSecondaryColor`| `$cloudlight` |
|`$ProgressCircleBgColor`| `$white` |
|`$ProgressCircleInnerShadow`| `0 0 3px 1px rgba(0, 0, 0, 0.05), 0 3px 1px 0 rgba(0, 0, 0, 0.05), 0 2px 2px 0 rgba(0, 0, 0, 0.10), 0 3px 3px 0 rgba(0, 0, 0, 0.05)` |
