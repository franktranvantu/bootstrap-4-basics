In this section, we'll build a basic page footer using the nav and dropdown button components. 

You'll learn how simple it is to add interactive components to your site, using JavaScript plugins.

Steps:
1. Build footer
    ```html
    <div class="row py-3">
        <div class="col-md-7">
          <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Community</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Tracks</a>
            </li>
            <li class="nav-item">
              <div class="btn-group dropup">
                <button type="button" class="btn btn-outline-secondary">Other Conf</button>
                <button type="button" class="btn btn-outline-secondary dropdown-toggle dropdown-toggle-split" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                  <span class="sr-only">Toggle Dropdown</span>
                </button>
                <div class="dropdown-menu">
                  <a class="dropdown-item" href="#">CSS Conf</a>
                  <a class="dropdown-item" href="#">Python Conf</a>
                  <a class="dropdown-item" href="#">Java Conf</a>
                  <a class="dropdown-item" href="#">Swift Conf</a>
                </div>
              </div>
            </li>
          </ul>
        </div>
        <div class="col-md text-md-right">
          <small>&copy; 2017 Full Stack Conf &amp; Treehouse</small>
        </div>
      </div>
    ```