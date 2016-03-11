# Bootstrap Lab

For this lab, consult the [bootstrap docs](http://getbootstrap.com/) liberally. __HINT__: check out the solution branch to check your work `git checkout solution`

1. In terminal, clone this repo.
```
git clone https://github.com/sf-wdi-27-28/bootstrap-boilerplate.git
```

1. Add this boilerplate navbar code above the `div` with the class `.container`.

  ```html
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <!-- Brand and toggle get grouped for better mobile display -->
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">Brand</a>
      </div>

      <!-- Collect the nav links, forms, and other content for toggling -->
      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="#">Link</a></li>
          <li class="dropdown">
            <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="#">Action</a></li>
              <li><a href="#">Another action</a></li>
              <li><a href="#">Something else here</a></li>
              <li role="separator" class="divider"></li>
              <li><a href="#">Separated link</a></li>
            </ul>
          </li>
        </ul>
      </div><!-- /.navbar-collapse -->
    </div><!-- /.container-fluid -->
  </nav>
  ```

  **Lorem Ipsum**: for the rest of these challenges, use [lorem ipsum](http://www.lipsum.com/feed/html) text to fill in your columns.

1. Using the bootstrap grid, make a grid that is 4 columns wide when on desktop (lg), 3 on laptop (md), 2 on tablet (sm), and 1 on mobile.

1. Using the bootstrap grid, make a grid that has one column, six units wide, with an offset of three on the left -- except for on mobile where the column is full width.

1. Using the bootstrap grid, make a three column grid that is 3-6-3 on desktop (lg), or 2-6-2 with 1 offset on tablet (sm). On mobile (xs), it should show as one column, and the leftmost column should be hidden.

# Stretch

Pick any website online, wireframe it on paper or whiteboard and create a simple bootstrap version with the bootstrap grid, navbar, lorem ipsum, and [Placehold.it](https://placehold.it/). (**Hint**: Use bootstrap's [image classes](http://getbootstrap.com/css/#images) to size images.)
