Forms can be difficult to style. 

Not only do form elements display differently in different browsers, but most browsers limit the visual changes you can make to form controls. 

In this section, we'll start using Bootstrap's form control styles to build the Full Stack Conf registration form.

```html
<form>
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" class="form-control" id="name">
  </div>
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" class="form-control" id="email">
  </div>
</form>
```