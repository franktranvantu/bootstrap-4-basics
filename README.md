Bootstrap simplifies many complex or time-consuming tasks like building navigations, from controls, drop down menus and more. 

In this section, we'll continue building the Full Stack Conf site using Bootstrap's UI components, starting with the navbar.

Steps:
1. Build navbar
    ```html
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#">Disabled</a>
          </li>
        </ul>
      </div>
    </nav>
    ```
 2. Display the navbar brand to the right of the navbar
    ```html
    <a class="navbar-brand order-1" href="https://teamtreehouse.com/" target="_blank">Presented by Treehouse</a>
    ```
 3. Change navbar background color
    ```html
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    ```
4. Align content inside the navbar
    ```html
     <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        ...
      </div>
     </nav>
    ```
5. Make the navbar brand end of the right side
    ```html
    <a class="navbar-brand order-1 mr-0" href="https://teamtreehouse.com/" target="_blank">Presented by Treehouse</a>
    ```
6. Fixed navbar on the top
    ```html
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    ```