# Spacing
#### I think we need some space

You can add some paddings to your element, just by adding `.ka-Spacing__base`class & you will have by default **16px** all around.

```html
<div class="ka-Spacing__base"><div>
```

Sizes
-----

We create differents sizes: 

| Size | Classname | Default | Calculation |
 |:----|:-----------:|---------|:-----------:|
|   X-Small   | `.ka-Spacing__xs` | 2px | `$SpacingBase / 8` |
|   Small  | `.ka-Spacing__sm` | 4px | `$SpacingBase / 4` |
|  Medium   | `.ka-Spacing__md` | 8px | `$SpacingBase / 2` |
|   **Base**   | `.ka-Spacing__base` | **16px** | **`$SpacingBase`**  |
|  Large  | `.ka-Spacing__lg` | 24px | `$SpacingBase *  1.5` |
|   X-Large  | `.ka-Spacing__xl` | 32px | `$SpacingBase * 2`  |
|   XX-Large   | `.ka-Spacing__xxl` | 40px | `$SpacingBase * 2.5`  |

***
Variables
------
You can use these variables to customize the Form and the Fieldset. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$SpacingBase` | 1rem |
