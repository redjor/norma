# Layout
#### We are in position
The Layout component helps you to design the structure of your app.

The structure is different than the normal, but it allows to pass classes from header & footer to the View element. 

?>If the **ViewHeader** is displayed so the **View** inherit from his parent.



```html
<div id="App">
  <!-- Header -->
  <div class="ViewHeader">
  </div>
  <!-- Main View -->
  <div class="View">
    <!-- Footer -->
    <div class="ViewFooter">
    </div>
    <!-- Page -->
    <div class="Page">
      <div class="PageContent">
        <!-- Put your content here -->
      </div>
    </div>
  </div>
</div>
```

?> The layout is displayed in **flexbox** with `flex-direction: column`.


## Flex
You can make your element flex with `is-flex` class.

## Justify
You can positionned your content according to the cross axis, with the following classes:

| Position  | Classname |
| ------- |:-----------:|
| Top | `flex__justify--top` |
| Center | `flex__justify--center` |
| Space Between | `flex__justify--between` |
| Bottom | `flex__justify--bottom` |

## Align
You can positionned your content according to the main axis, with the following class:

| Position  | Classname |
| ------- |:-----------:|
| Left | `flex__align--left` |
| Center | `flex__align--center` |
| Right | `flex__align--right` |

## Grow

The element could take the whole height by adding `flex__grow--auto` class to your flex element.

## Helpers
||Classname||
|:----------|:------------|:---------------------|
| **Spacing**  | `noPadding`| Removes any padding |
|| `noMargin` | Removes any margin |

***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$LayoutHeaderHeight` | `48px` |
|`$LayoutFooterHeight` | `48px` |