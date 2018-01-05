<template>
  <div class="app">
    <nav class="navbar navbar-expand-md navbar-light bg-light fixed-top">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler border-0" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
        <i class="fa fa-bars"></i>
      </button>

      <div class="collapse navbar-collapse" id="navbarsExampleDefault">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#">Disabled</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="http://example.com" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Dropdown</a>
            <div class="dropdown-menu" aria-labelledby="dropdown01">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul>
        <form class="form-inline my-2 my-lg-0">
          <div class="input-group">
            <input class="form-control" type="text" placeholder="Search" aria-label="Search">
            <div class="input-group-append">
              <button class="btn btn-primary" type="submit">
                <i class="fa fa-search"></i>
              </button>
            </div>
          </div>
        </form>
      </div>
    </nav>

    <main role="main" class="container">
      <router-view></router-view>
    </main><!-- /.container -->
  </div>
</template>

<script>
export default {
  name: 'full'
}
</script>