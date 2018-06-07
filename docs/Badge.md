# Badge
#### It's written on my shirt
The badge provides a background color with rounded borders to a number element.

<div class="demo-block">
  <div class="ka-Badge">100+</div>
</div>

```html
<div class="ka-Badge">100+</div>
```
***
Variables
------
You can use these variables to customize the badge. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$BadgeColor`| `white` |
|`$BadgeBgColor`| `black` |
|`$BadgeFontSize`| `14px` |
|`$BadgeRadius`| `ceil($BadgeFontSize) * 1.5` |