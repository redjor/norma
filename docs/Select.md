# Select
#### Make your choice more easily


<div class="demo-block" style="display: block;">
  <label class="ka-Select" for="id">
    <label class="ka-Select__label">Select</label>
    <select class="ka-Select__select" name="" id="{{id}}" placeholder="placeholder" {{attributes}}>
        <option class="ka-select__option" value="" selected>Option 1</option>
    </select>
  </label>
</div>

```html
<label class="ka-Select" for="ID">
  <label class="ka-Select__label">Select</label>
  <select class="ka-Select__select" name="" id="ID" placeholder="placeholder">
      <option class="ka-select__option" value="" selected>Option 1</option>
  </select>
</label>
```

You can make it fullwidth by adding `is-fullwidth` to the `ka-Select`.

***
Variables
------
You can use these variables to customize it. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |-----------:|
| `$SelectLabelFontSize`| `12px` |
| `$SelectLabelColor`| `$darklight` |
| `$SelectBgColor`| `transparent` |
| `$SelectFontSize`| `16px` |
| `$SelectHeight`| `16px` |
| `$SelectColor`| `$purpledark` |
| `$SelectChevronColor`| `$black` |