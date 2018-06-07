# Typography
#### Too much character ?

Use the differents text styles to make your app more readable.

<div class="demo-block" style="height: 500px;display: flex;flex-direction: column;justify-content: space-around;">
  <div class="text-style-large-title">Large title</div>
  <div class="text-style-title1">Title 1</div>
  <div class="text-style-title2">Title 2</div>
  <div class="text-style-title3">Title 3</div>
  <div class="text-style-headline">Headline</div>
  <div class="text-style-body">Body</div>
  <div class="text-style-callout">Callout</div>
  <div class="text-style-subhead">Subhead</div>
  <div class="text-style-footnote">Footnote</div>
  <div class="text-style-caption1">Caption 1</div>
  <div class="text-style-caption2">Caption 1</div>
</div>

?>In order to stylizing your element, add `.text-style-body` class.

## Family
By default, we don't use other fonts than **System fonts**
```css
font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif
```


## Sizes
You have the choice between multiples styles:

| Name | Size |  Weight |  Line Height | Spacing  | Classname |
|:----|:----:|:---------:|:-----------:|:-----------:|:---------:|
|Large title| 34px|  700|  41px| -0.039px | `.text-style-large-title`|
|Title 1| 28px| 400|  34px| -0.036px | `.text-style-title1`|
|Title 2| 22px| 400| 28px| -0.035px | `.text-style-title2`|
|Title 3| 20px| 400| 25px| -0.038px | `.text-style-title3`|
|Headline| 17px| bold| 22px| -0.041px | `.text-style-headline`|
|**Body**| **16px**| **400**| **22px**| **-0.041px** | **`.text-style-body`**|
|Callout| 15px| 400| 18px|  -0.024px | `.text-style-callout`|
|Subhead| 14px| 500|  20px|  -0.024px | `.text-style-subhead`|
|Footnote| 13px| 400| 18px| 0 | `.text-style-footnote`|
|Caption1| 12px| 400| 16px| 0 | `.text-style-caption1`|
|Caption2| 11px| 400| 16px| 0 | `.text-style-caption2`|


## Alignement
We provide some helpers with the following class, in order to align your text.

|Alignement|Classname|
|:--------:|:-------:|
|Left|`.has-text-left`|
|Center|`.has-text-center`|
|Right|`.has-text-right`|
|Justify|`.has-text-justify`|


## Colors
!> More colors will be added soon

You can directly change the text color by adding `.has-black-text` class to it.

>white, black, dark, cloud, danger, success, warning, info