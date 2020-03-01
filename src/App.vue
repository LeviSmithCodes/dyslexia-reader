<template>
  <div id="app" class="app container-fluid">
    <router-view />
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

.app {
  background: url("https://cdn.pixabay.com/photo/2016/07/08/11/32/texture-1504100_1280.jpg")
    repeat center;
  background-size: cover;
  min-height: 100vh;
  /* opacity: 0.6; */
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
}
</style>
