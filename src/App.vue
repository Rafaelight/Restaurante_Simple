<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Inicio</router-link>
      <router-link to="/Inventario">Inventario</router-link>
      <router-link to="/about">Nosotros</router-link>
      <router-link to="/articulo">Articulos</router-link>
    </div>
    <router-view/>
  </div>
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
  padding: 30px;
  margin-top: 0px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  margin: 10px 10px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
