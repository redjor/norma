# Form
#### Can you fill it ?

The Form component helps you to contain and order your form controls with style.

<div class="demo-block">
  <div class="ka-Form">
    <div class="ka-Form__wrapper is-rounded is-bordered">
      <div class="ka-Form__container--title">Title</div>
      <div class="ka-Form__container">
        <div class="ka-Form__item ka-Spacing__base">
          Add your form control
        </div>
      </div>
      <div class="ka-Form__container--description">Description</div>
    </div>
  </div>  
</div>

```html
<div class="ka-Form">
  <!-- The form is always wrapped -->
  <div class="ka-Form__wrapper">
    <!-- You can add a title -->
    <div class="ka-Form__container--title">Title</div>
    <!-- Always put Item in his container -->
    <div class="ka-Form__container">
      <!-- You can add as many as you want -->
      <div class="ka-Form__item"></div>
    </div>
    <!-- You can add a helper text or a description -->
    <div class="ka-Form__container--help"></div>
    <div class="ka-Form__container--description">Description</div>
  </div>
</div>  
```

## Container
The `ka-Form__item`needs to be contained in the `ka-Form__container`, placed in `ka-Form__wrapper`.

```html
<div class="ka-Form">
  <div class="ka-Form__wrapper">
    <div class="ka-Form__container"></div>
  </div>
</div>  
```
- You can separated every items with borders by adding `has-divider` to the container.
- If you need some paddings inside the container, add `ka-Form__container--inset` to it.

## Item
Every control needs to be wrapped into `ka-Form__item`.
```html
<div class="ka-Form__container">
    <!-- You can add as many as you want -->
    <div class="ka-Form__item"></div>
</div>
```
** Inset ** : You can paddings to your item by adding `ka-Form__item--inset`.

## Title
You can add a title to your Form by adding an element with `ka-Form__container--title` just above the container.
```html
<div class="ka-Form__container--title"></div>
<!-- Always put Item in his container -->
<div class="ka-Form__container"></div>
```

## Help & Description
A description or an help message could be displayed below the `ka-Form__container`.

```html
<div class="ka-Form__container"></div>
<!-- You can add a  helper text or a description -->
<div class="ka-Form__container--help"></div>
<div class="ka-Form__container--description"></div>
```


## Styles
You can add the following classes to any Form element:
- `is-rounded` class changes border radius to 5.5px by default.
- `is-bordered` class adds some borders.

?> By default, the container doesn't have any background color.  If you have the **Background component**, you can add a background-color like `.has-white-bg` for example.

***

## Fieldset

This fieldset doesn't use some modifiers. Just follow the following stucture.

```html
<fieldset class="ka-Fieldset">
  <legend class="ka-Fieldset__legend"></legend>
  <div class="ka-Fieldset__container">
    <div class="ka-Fieldset__item"></div>
  <div class="ka-Fieldset__description"></div>
  </div>
</fieldset>
```
***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$formBorderColor` | `rgba(0,0,0,.15)` |
|`$formBorderRadius` | `5.5px` |
|`$formBorderSize` | `1px` |
|`$formWrapperMrgBottom` | `1rem` |
|`$formItemInset` | `1rem` |
|`$formContainerTitleColor` | `black` |
|`$formContainerTitleBgColor` | `transparent` |
|`$formContainerBgColor` | `white` |
|`$formContainerPadding` | `.5rem .5rem .5rem 1rem` |
|`$formDescriptionColor` | `grey` |
|`$formDescriptionBgColor` | `lightgrey` |
|`$formHelpColor` | `darkblue` |
|`$formHelpBgColor` | `lightblue` |
|`$formHelpPadding` | `.5rem 1rem .5rem 1.75rem` |

