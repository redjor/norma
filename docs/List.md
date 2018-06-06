# List
#### Keep it in order

<a href="https://ibb.co/gWcRyT"><img src="https://image.ibb.co/mtyAQ8/list.png" alt="list" border="0" height="140px"></a>

A list needs to be contained in an element with `.ka-List` class.


```html
<ul class="ka-List ">
  <li class="ka-List__item">
    <div class="ka-List__item--left"></div>  
    <div class="ka-List__item--center"></div>
    <div class="ka-List__item--right"></div>
  </li>
</ul>
```
### Title
A title could be displayed just above the List by adding an element with `ka-List__title` class.
```html
<div class="ka-List__title"></div>
<div class="ka-List"></div>
```

### Caption
A caption could be displayed just below the List by adding an element with `ka-List__caption` class.
```html
<div class="ka-List"></div>
<div class="ka-List__caption"></div>
```

### Styles
The `ka-List` can be stylized with the following class:
- **No Border** `.ka-List__noborder` class removes all borders.
- **Inset** `.ka-List__inset` class adds borders with radius and side margins.
- **Rounded** `.ka-List__rounded` class adds somes border radius *(5.5px by default)*
- **Shadow** `.ka-List__shadow`class adds a shadow.

***

## List Item

You need to put at least a `.ka-List__item` class element into `.ka-List`, and you can add as many as you want.

The list item adapt his height depends on his content, but it has a min-height *(default: 54px)*.

```html
<div class="ka-List__item">
  <div class="ka-List__item--left"></div>  
  <label class="ka-List__item--center"></label>
  <div class="ka-List__item--right"></div>
</div>
```

> **Any Element**
> You can add any other element into `.ka-List__item`, like text inputs, radio, checkbox, switch and many things

### Header
The header `ka-List__header` is like a title but contains in the List container. It needs to be placed just above the List item
```html
<div class="ka-List__header"></div>
<!-- Always above the first item -->
<div class="ka-List__item"></div>
```

###  Left
The left element with needs to have `ka-List__item--left` class and can contains the following elements inside:
-  **Thumbnail** : Add an element with `ka-List__item--thumbnail` to contains an icon or an image inside the left item.

### Center
The left element with needs to have `ka-List__item--center` class and can contains the following elements inside:
-  **Title** : `.ka-List__item--title`
-  **Subtitle** :`.ka-List__item--subtitle`

###  Right
The left element with needs to have `ka-List__item--right` class and can contains the following elements inside:
- **Label** : `.ka-List__item--label`
- **Icon**: `.ka-List__item--icon`
- **Chevron** : A chevron can be displayed just add `.ka-List__item--chevron` but if you have some elements on the right item, so you need to add `.ka-List__item--chevron__right` to `.ka-List__item--right` in order to add some padding.
```html
<div class="ka-List__item ka-List__item--chevron">
  <div class="ka-List__item--right ka-List__item--chevron__right"></div>
</div>
```

### Styles

The list item can have multiples styles by adding those following class: 

- **Tappable** `.ka-List__item--tappable` class provided an effect for linkable element on mobile.
- **Long Divider** `.ka-List__item--longdivider` class make the divider fullwidht
- **No Divider** `ka-List__item--nodivider__center` & `ka-List__item--nodivider__right` class removes all dividers
- **No Padding** `.ka-List__item--nopadding` // Will be deprecated

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
| `$listLabelColor`| black |
| `$listBgColor`| white |
| `$listInsetRadius`| 5.5px |
| `$listBorderColor`| #BCBBC1 |
| `$listShadow`| 0 .1rem .2rem .1rem rgba(0,0,0,.1) |
| Title ||
| `$listTitleColor`| black |
| `$listTitleBgColor`| transparent |
| `$listTitlePadding`| 4px 16px |
| Header ||
| `$listHeaderHeight`| 2rem |
| `$listHeaderColor`| black |
| `$listHeaderBgColor`| #F8F8F8 |
| List Item ||
| `$listItemHeight`| 54px |
| `$listItemColor`| black |
| `$listItemTitleColor`| black |
| `$listItemSubtitleColor`| grey |
| `$listItemBorderColor`| lightgrey |
| `$listThumbnailRadius`| 4px |
| `$listChevronColor`| black |