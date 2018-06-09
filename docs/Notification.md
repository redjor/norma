# Notification
#### We have a message for you
The Notification component helps you to display messages & feedbacks to your users.

Create a Notification component by added `ka-Notification` class to your element. After that, you can specify the type of alert who want to display.

<div class="demo-block has-cloudlight-bg">
<div class="ka-Notification">
    <div class="ka-Notification__content">
      <!-- Icon for closing the notification -->
      <i class="fa far fa-times-circle"></i>
      <!-- Enter your message -->
      <span>Regular message: *By default*</span>
    </div>
  </div>
  <div class="ka-Notification is-info">
    <div class="ka-Notification__content">
      <!-- Icon for closing the notification -->
      <i class="fa far fa-times-circle"></i>
      <!-- Enter your message -->
      <span>Info message: `is-info`</span>
    </div>
  </div>
    <div class="ka-Notification is-success">
    <div class="ka-Notification__content">
      <!-- Icon for closing the notification -->
      <i class="fa far fa-times-circle"></i>
      <!-- Enter your message -->
      <span>Success message: `is-success`</span>
    </div>
  </div>
    <div class="ka-Notification is-danger">
    <div class="ka-Notification__content">
      <!-- Icon for closing the notification -->
      <i class="fa far fa-times-circle"></i>
      <!-- Enter your message -->
      <span>Danger message: `is-danger`</span>
    </div>
  </div>
    <div class="ka-Notification is-warning">
    <div class="ka-Notification__content">
      <!-- Icon for closing the notification -->
      <i class="fa far fa-times-circle"></i>
      <!-- Enter your message -->
      <span>Warning message: `is-warning`</span>
    </div>
  </div>
  
</div>


```html
<div class="ka-Notification">
  <div class="ka-Notification__content">
    <!-- Icon for closing the notification -->
    <i class="fa far fa-times-circle"></i>
    <!-- Enter your message -->
    <span>Message</span>
    <!-- Add an action button here -->     
    <button class="ka-Button">Label</button>
  </div>
</div>
```

***
Variables
------
You can use these variables to customize this element. Simply set one or multiple of these variables in `scss/styles/base.scss`.

| Name  | Default value |
| ------- |:-----------:|
| `$NotificationBorderSize`| `1px `|
| `$NotificationBorderRadius`| `5.5px `|
| `$NotificationPadding`| `1rem `|
| `$NotificationBgOpacity`| `.95 `|