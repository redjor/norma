# Modal
#### Push me to the top
The Modal component displays content above the view with an animation from the bottom.

<div class="demo-block" style="height: 300px;">
  <div id="modalID" class="ka-Modal modal-show has-white-bg" data-modal-effect="slip-bottom" style="position: absolute;">
    <!-- You always need to wrapper the content -->
    <div class="ka-Modal__wrapper">
      <!-- Title -->
      <header class="ka-Modal__header has-dark-bg">
        <div class="ka-Navbar ka-Navbar__dark">
          <div class="ka-Navbar__center ">
            <div class="ka-Navbar__center--container"> 
              <span class="ka-Navbar__title">Modal</span>
            </div>
          </div>
        </div>
      </header>
      <!-- Content -->
      <div class="ka-Modal__content ka-Spacing__base">
        <div class="text-style-caption1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur justo felis, commodo vel lorem sed, faucibus ullamcorper nibh. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Integer consectetur tincidunt urna, eget tristique est laoreet nec. Curabitur rutrum neque in ante dignissim sodales. Cras mollis, turpis eget viverra semper, diam enim sollicitudin dolor, eu pretium quam orci eget risus. Vivamus id molestie tellus, quis porttitor magna. Donec dignissim, ligula id dictum vulputate, lacus mi vulputate neque, et imperdiet lacus dolor eget nulla. Nulla nunc lacus, ultricies vehicula laoreet vel, dictum consequat dolor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.
        </div>
      </div>
      <!-- Footer -->
      <footer class="ka-Modal__footer has-cloudlight-bg">
        <div class="ka-Spacing__md">
          <button class="ka-Button small ka-Button--dark is-fullwidth">Button</button>
        </div>
      </footer>
    </div>
  </div>
      <div class="ka-Modal__overlay" style="position: absolute; opacity: .5; visibility: visible;"></div>
</div>

```html
<div id="ID" class="ka-Modal" data-modal-effect="slip-bottom">
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

?> The Modal component doesn't have any background or padding.
***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$modalBorderRadius` | `5.5px` |
|`$modalMaxWidth` | `640px` |
|`$modalShadow` |  `0 31px 41px 0 rgba(0,0,0,.2), 0 2px 16px 0 rgba(0,0,1,.08)` |
|`$modalHeaderBorderColor` | `#F8F8F8` |
|`$modalClosingAreaColor` | `rgba($dark, .25)` |
|`$modalOverlayColor` | `black` |
|`$modalZIndex` | `999` |