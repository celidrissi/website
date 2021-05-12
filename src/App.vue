<template>
    <div class="container-fluid">
      <div class="row">
        <div id="nav" class="col-12">
          <router-link to="/">Home</router-link> |
          <router-link to="/about">A Propos</router-link> |
          <router-link to="/about">Contact</router-link>
        </div>
        <div class="row">
          <div class="col">
            <img src="@/assets/photo.jpg" class="img-fluid">
          </div>
          <div class="col"> TEXTE </div>
        </div>
        
      </div>
    </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 10px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}


</style>
