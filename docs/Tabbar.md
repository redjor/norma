# Tabbar

!> Redaction in Progress


```html
  <div class="ka-Tabbar">
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

```html
      <i class="ka-Tabbar__icon fa far fa-{{tab.icon}}"></i>
      <div class="ka-Tabbar__label">{{tab.label}}</div>
      <span class="ka-Badge">{{tab.notifications}}</span>
```

`ka-Tabbar__{{position}}`
`ka-Tabbar__bordered`
`ka-Tabbar__dark`


***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$tabbarHeight`| 48px |
|`$tabbarFontSize`| 16px |
|`$tabbarBorderSize`| 4px |
|`$tabbarIconSize`| ceil( $tabbarHeight * 0.4 ) |
|`$font`|family: -apple-system, helvetica, arial, sans-serif |
| **Light mode** | |
|`$tabbarColor`| grey |
|`$tabbarActiveColor`| black |
|`$tabbarBgColor`| white |
|`$tabbarBadgeColor`| white |
|`$tabbarBadgeBgColor`| black |
|`$tabbarActiveTabBorderColor`| black |
|`$tabbarBorderColor`| #F8F8F8 |
| **Dark mode** ||
|`$tabbarDarkActiveColor`| white |
|`$tabbarDarkColor`| grey |
|`$tabbarDarkBgColor`| black |
|`$tabbarDarkBadgeColor`| white |
|`$tabbarDarkBadgeBgColor`| black |
|`$tabbarDarkActiveTabBorderColor`| grey |
|`$tabbarDarkBorderColor`| black |
