# Button
#### Don't push me too hard

<a href="https://ibb.co/g6zCSo"><img src="https://image.ibb.co/evpqDT/button.png" alt="button" border="0" height="128"></a>

The Button component displays a regular button with differents styles and colors.

The `ka-Button` class can be used on:

- `<a>` anchor links
- `<button>` form buttons
- `<input type="submit">` submit inputs
- `<input type="reset">` reset inputs

```html
<button class="ka-Button"></button>
```
Styles
------
By default, the button is stylized with plain color and a border. But you can add some classes to change it.

- **Outlined** :
Add `is-outlined` class change the fill transparency and keep the border.
-  **Rounded** :
Add `is-rounded` class change the border radius to 60px.
- **Fullwidth** :
Add `is-fullwidth` class makes it 100% width:
- **Dark mode** :
Add `dark-mode` class change it to be ready with dark background. 
- **Disabled** :
Use the HTML5 attributes `disabled` will added some opacity to it.


Colors
-------

```html
<button class="ka-Button ka-Button--white"></button>
```

| Colorname | Classname |
|:-------------|:----------:|
|   White   | `ka-Button--white` |
|   Light   | `ka-Button--light` |
|   Dark   | `ka-Button--dark` |
|   Black   | `ka-Button--black` |
|  Primary   | `ka-Button--primary` |
|   Link   | `ka-Button--link` |
|   Success   | `ka-Button--success` |
|  Warning  | `ka-Button--warning` |
|   Info   | `ka-Button--info` |
|   Danger   | `ka-Button--danger` |

Sizes
------
We have 3 differents sizes based on the **normal** size:

| Size        | Class  | Height  |
| ------------- |:-------------:| -----:|
| Small      | `small` | $buttonHeight\*0.8 |
| Normal   |   |   $buttonHeight  |
| Large | `large`  |   $buttonHeight\*1.2  |

Icons
------
You can add some icons with the [Font Awesome](https://fontawesome.com/icons). You can put it on the left or on the right side of the label.

```html
<button class="ka-Button">
  <!-- Icon on the left -->
    <span class="icon"><i class="fa far fa-icon"></i></span>
    <span>Label</span>
  <!-- Icon on the right -->
  <span class="icon"><i class="fa far fa-icon"></i></span>
</button>
```

Buttons
--------
If you want to group buttons together, wrap them in a `ka-Buttons` element:
```html
<div class="buttons">
  <button class="ka-Button"></button>
  <button class="ka-Button"></button>
</div>
```

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
|`$buttonHeight`| 48px |
|`$buttonFontSize`| 16px |
|`$buttonRadius`| 5.5px |
|`$buttonDisabledOpacity`| .5 |
|`$buttonsMargin`| .5rem |

> More to come
> - [ ] Loading
> - [ ] Active
> - [ ] Focus
