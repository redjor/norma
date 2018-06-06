# Map
#### Here we are

The map component displays a google maps with custom controls on the top right.

``` html
<div class="ka-Map">
  <!-- Controls -->
  <div class="ka-Map__controls">
    <div class="ka-Map__controls--container">
      <button class="ka-Map__control" id="centerCar">
        <i class="fa far fa-car"></i>
      </button>
      <button class="ka-Map__control" id="centerUser">
        <i class="fa far fa-location-arrow"></i>
      </button>
    </div>
  </div>
  <!-- Use the following div to display the map. -->
  <div id="Map"></div>
</div>
```

## Disabled control
You can disabled a control by added the **disabled** attribute to the button.

```html
<button class="ka-Map__control" disabled></button>
```

?> You can add our own map plugin by using the `#Map` element.

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$MapControlsBgColor `| white |
|`$MapControlsColor `| $dark |
|`$MapControlsShadow `| 0 1px 3px 0 rgba(0,0,0,.2), 0 3px 6px 0 rgba(0,0,0,.08) |
|`$MapControlsRadius `| 5.5px |
|`$MapControlWidth `| 44px |
|`$MapControlFontSize `| 18px |
|`$MapControlBorderColor `| $cloud |