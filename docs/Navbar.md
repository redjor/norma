# Navbar
#### You are in control

The Navbar component is as the navigational toolbar. A navbar can contain a title, buttons, segment, or a searchbar. Navbars must be placed in header or footer.

<div class="demo-block has-cloudlighter-bg">
  <div class="ka-Navbar has-white-bg">
    <!-- Left -->
    <div class="ka-Navbar__left">
      <span class="ka-Navbar__button">
        <i class="fa far fa-chevron-left"></i>
      </span>
    </div>
    <!-- Right -->
    <div class="ka-Navbar__right">
      <span class="ka-Navbar__button ka-Navbar__button--outlined">Cancel</span>
    </div>
    <!-- Center -->
    <div class="ka-Navbar__center">
      <div class="ka-Navbar__item">
        <!-- Add element here -->
      </div>
      <div class="ka-Navbar__center--container">
        <span class="ka-Navbar__title">Title</span>
      </div>
    </div>
  </div>
</div>

```html
<div class="ka-Navbar">
  <!-- Left -->
  <div class="ka-Navbar__left">
    <span class="ka-Navbar__button">
      <i class="fa far fa-chevron-left"></i>
    </span>
  </div>
  <!-- Right -->
  <div class="ka-Navbar__right">
    <span class="ka-Navbar__button ka-Navbar__button--outlined">Cancel</span>
  </div>
  <!-- Center -->
  <div class="ka-Navbar__center">
    <div class="ka-Navbar__center--container">
      <span class="ka-Navbar__title">Title</span>
    </div>
  </div>
</div>
```

## Title & Subtitle
The title and the subtitle are wrapped into `ka-Navbar__center--container`. 

```html
<div class="ka-Navbar__center">
  <!-- Wrap your content in this container -->
  <div class="ka-Navbar__center--container">
    <span class="ka-Navbar__title">Title</span>
    <span class="ka-Navbar__subtitle">Subtitle</span>
  </div>
</div>
```  

## Center Item
If you want to add a segment, a search or an input, you need to put it in an element with `ka-Navbar__item` class.
```html
<div class="ka-Navbar__center">
  <div class="ka-Navbar__item">
    <!-- Insert an element here -->
  </div>
</div>
```

## Button
A button can be displayed in the navbar with `ka-Navbar__button` class on the left & the right side.
```html
<span class="ka-Navbar__button">Label</span>
```
**Outlined** : You can add a border to the button with `ka-Navbar__button--outlined`.



## Icon
Add your icon in `ka-Navbar__button`.
```html
<span class="ka-Navbar__button">
  <i class="fa far fa-chevron-left"></i>
</span>
```

## Theme
**Dark**

If you want to use your navbar on dark background, just add `ka-Navbar__dark` to `ka-Navbar`.

***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$NavbarHeight`| `44px` |
|`$NavbarTitleFontSize`| `15px` |
|`$NavbarButtonFontSize`| `15px` |
|`$NavbarButtonBorderColor`| `$cloud` |
| Light Theme||
|`$NavbarTitleColor`|`$black` |
|`$NavbarSubtitleColor`| `lighten($black, 20%)` |
|`$NavbarButtonColor`| `$black` |
|`$NavbarBgColor`| `$white` |
| Dark Theme ||
|`$NavbarDarkTitleColor`| `$white` |
|`$NavbarDarkSubtitleColor`| `lighten($NavbarDarkTitleColor, 20%)` |
|`$NavbarDarkButtonColor`| `$white`|
|`$NavbarDarkBgColor`| `$black` |
|`$NavbarDarkButtonBorderColor`| `$dark-lighter` |
