# Textarea
#### Tell us your story

The Textarea component is wrapped into `ka-Textarea` to keep control on the design. By default, we have the same height thant the text input but with the JS function, we grow his height with the text. 

<div class="demo-block">
 <div class="ka-Textarea">
   <label class="ka-Textarea__label" for="">Description</label>
   <textarea class="ka-Textarea__textarea" placeholder="Tell us your story" name="" id="" rows="1"></textarea>
 </div>
</div>

```html
 <div class="ka-Textarea">
   <label class="ka-Textarea__label" for="">Description</label>
   <textarea class="ka-Textarea__textarea" placeholder="" name="" id="" rows="1"></textarea>
 </div>
```
### Label
You can remove the label in order to only keep the textarea.

### AutoResize function
We use a JS function to automaticaly resize the textarea height according to the text height.
```js
var textarea = document.querySelector('textarea');
var textareaContainer = document.querySelector('.ka-Textarea');
             
function autosize(){
  var el = this;
  setTimeout(function(){
    el.style.cssText = 'height:auto; padding:0';
    textareaContainer.style.cssText = 'height:auto; padding:0';
    el.style.cssText = 'height:' + el.scrollHeight + 'px';
  },0);
}; 

if(textarea){
  textarea.addEventListener('keydown', autosize);
}
```

!> Use your own JS function if you can.

Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
| `$TextareaLabelColor`| `$darklightest` |
| `$TextareaFontSize`| `15px` |
| `$TextareaColor`| `$black` |
| `$TextareaBgColor`| `$white` |