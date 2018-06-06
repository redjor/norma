# Modal
#### Push me to the top

The Modal component displays content behind the view with an animation from the bottom.

```html
<div id="modalID" class="ka-Modal" data-modal-effect="slip-bottom">
  <!-- You always need to wrapper the content -->
  <div class="ka-Modal__wrapper">
    <!-- Title -->
    <header class="ka-Modal__header"></header>
    <!-- Content -->
    <div class="ka-Modal__content"></div>
    <!-- Footer -->
    <footer class="ka-Modal__footer"></footer>
  </div>
</div>
```

## Appearance
The modal appear with an animation by adding the `modal-show` class to `ka-Modal`.

## Overlay
The overlay can be add directly before or after the modal. In order to make it visible with an animation, you need to add `modal-show` class to `ka-Modal__overlay`.

## Adding a closing area
You can add a closing area on the top of modal with `ka-Modal__closing-area`

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$modalBorderRadius` |  5.5px |
|`$modalMaxWidth` |  640px |
|`$modalShadow` |  0 31px 41px 0 rgba(0,0,0,.2), 0 2px 16px 0 rgba(0,0,1,.08) |
|`$modalHeaderBorderColor` |  #F8F8F8 |
|`$modalClosingAreaColor` |  rgba($dark, .25) |
|`$modalOverlayColor` |  black |
|`$modalZIndex` |  999 |