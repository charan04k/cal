<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Calender</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">+
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Today</button>
      </li>
      
      
    </ul>
    <form class="form-inline my-2 my-lg-0">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      <a class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Day</a>
          <a class="dropdown-item" href="#">Weekly</a>
          <a class="dropdown-item" href="#">Monthly</a>
          <a class="dropdown-item" href="#">Yearly </a>
        </div>
      </a>
    </form>
  </div>
</nav>
</template>

<script>
export default {

}
</script>

<style>
 header{
    text-align: center;
    width: 100%;
    background: salmon;
    padding-top: 10px;
    display: inline;
}

</style>