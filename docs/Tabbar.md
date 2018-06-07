# Tabbar
#### A remote for views
The Tabbar helps you to switch between differents views.
<div class="demo-block">
  <div class="ka-Tabbar ka-Tabbar--top ka-Tabbar__dark ka-Tabbar__bordered">
    <label class="ka-Tabbar__item">
      <input type="radio" name="name" checked>
      <button class="ka-Tabbar__button">
        <div class="ka-Tabbar__button--content">
          <div class="ka-Tabbar__label">Tab 1</div>
        </div>
      </button>
    </label>
    <label class="ka-Tabbar__item">
      <input type="radio" name="name">
      <button class="ka-Tabbar__button">
        <div class="ka-Tabbar__button--content">
          <div class="ka-Tabbar__label">Tab 2</div>
          <span class="ka-Badge">99+</span>
        </div>
      </button>
    </label>    
  </div>
</div>

```html
<div class="ka-Tabbar">
  <!-- One Tab -->
  <label class="ka-Tabbar__item">
    <input type="radio" name="name">
    <button class="ka-Tabbar__button">
      <div class="ka-Tabbar__button--content">
        <!-- Your content here -->
      </div>
    </button>
  </label>
</div>
```
### Tab with bottom border
If you need to add a bottom bar to the active tab, you need to add `ka-Tabbar__bordered` class to `ka-Tabbar`.

### Dark Theme
The Tabbar is ready for a dark background. You just need to trigger `ka-Tabbar__dark` class to 'ka-Tabbar'.

***
## Tab
A tab can contained a `label`, an `icon` or a `badge`. 

```html
<div class="ka-Tabbar__button--content">
  <i class="ka-Tabbar__icon fa far fa-globe"></i>
  <div class="ka-Tabbar__label">Label</div>
  <span class="ka-Badge">99+</span>
</div>
```

***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$tabbarHeight`| `48px` |
|`$tabbarFontSize`| `16px` |
|`$tabbarBorderSize`| `4px` |
|`$tabbarIconSize`| `ceil( $tabbarHeight * 0.4 )` |
|`$font`| `family: -apple-system, helvetica, arial, sans-serif` |
| **Light mode** | |
|`$tabbarColor`| `grey` |
|`$tabbarActiveColor`|`black` |
|`$tabbarBgColor`| `white` |
|`$tabbarBadgeColor`| `white` |
|`$tabbarBadgeBgColor`| `black` |
|`$tabbarActiveTabBorderColor`| `black` |
|`$tabbarBorderColor`| `#F8F8F8` |
| **Dark mode** ||
|`$tabbarDarkActiveColor`| `white` |
|`$tabbarDarkColor`| `grey` |
|`$tabbarDarkBgColor`| `black` |
|`$tabbarDarkBadgeColor`| `white` |
|`$tabbarDarkBadgeBgColor`| `black` |
|`$tabbarDarkActiveTabBorderColor`| `grey` |
|`$tabbarDarkBorderColor`| `black` |
