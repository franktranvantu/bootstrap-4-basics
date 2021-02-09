List groups are flexible UI components for displaying both simple and complex lists of elements. 

You can convert a simple HTML list into something more visually interesting.

Steps:
1. Build schedule
    ```html
    <ul class="list-group">
      <li class="list-group-item">
        <div class="d-flex justify-content-between">
          <h5>Keynote: Internet of Things</h5>
          <span class="badge badge-pill badge-info p-2">9:00 am</span>
        </div>
        <p class="mb-1">NodeStradamus</p>
      </li>
      <li class="list-group-item">
        <div class="d-flex justify-content-between">
          <h5>React Basics</h5>
          <span class="badge badge-pill badge-info p-2">10:00 am</span>
        </div>
        <p class="mb-1">Vivianne McVue</p>
      </li>
      <li class="list-group-item">
        <div class="d-flex justify-content-between">
          <h5>Hey, Mongo!</h5>
          <span class="badge badge-pill badge-info p-2">11:00 am</span>
        </div>
        <p class="mb-1">Jay Query</p>
      </li>
      <li class="list-group-item list-group-item-success">
        <div class="d-flex justify-content-between">
          <h5>Lunch</h5>
          <span class="badge badge-pill badge-info p-2">12:00 pm</span>
        </div>
        <p class="mb-1">Free pizza for everyone!</p>
      </li>
    </ul>
    ```