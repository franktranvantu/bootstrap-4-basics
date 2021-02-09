The registration form needs to let users select their job role from a menu. 

In this section, we'll use `.form-group` and `.form-control` to display a `<select>` menu.

```html
<div class="form-group">
  <label for="role">Job Role:</label>
  <select id="role" class="form-control">
    <option value="front end developer">Front End Developer</option>
    <option value="back end developer">Back End Developer</option>
    <option value="designer">Designer</option>
    <option value="student">Student</option>
  </select>
</div>
```