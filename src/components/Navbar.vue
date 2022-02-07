<template>

  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">

      <div class="collapse navbar-collapse justify-content-center navbar-light" id="navbarNavDropdown">
        <ul class="navbar-nav">

        <li class="nav-item p-3">
            <a class="nav-link" href="#">home</a>
        </li>
    
        <li class="nav-item p-3">
            <a class="nav-link" href="#">article</a>
        </li>
        <li class="nav-item p-3">
            <a class="nav-link" href="#">about</a>
        </li>
        <li class="nav-item p-3">
            <a class="nav-link" href="#">contact</a>
        </li>
          
        </ul>
      </div>
    </div>
  </nav>


</template>

<script>
export default {
  name: "Navbar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

li:hover {
    background: #222;
    
}

a {
    font-weight: 700 !important;
    color: #333 !important;
    text-transform: uppercase;
}

a:hover {
    color: #fff !important;
}

</style>
