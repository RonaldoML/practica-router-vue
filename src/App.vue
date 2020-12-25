<template>
  <div id="app">
    <div class="container">
      <ul class="nav justify-content-center">
        <li class="nav-item">
          <router-link class="nav-link active" to="/">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link active" to="/about">About</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/contacto">Contactos</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/Usuarios">Usuario</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/Productos">Productos</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/Login">Login</router-link> 
        </li>
      </ul>
    </div>
    <router-view />
  </div>
</template>

<style>
@import "../node_modules/bootstrap/dist/css/bootstrap.min.css"; /* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
