<template>
  <div id="app">
    <div id="nav">
      <img alt="Vue logo" :src="require('@/assets/logo.png')">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  height: 40px;
}

#nav img {
  height: 100%;
  float: left;
}

#nav a {
  font-weight: bold;
  color: #0080FF;
  padding: 10px;
  float: right;  text-decoration: none;
}
a:hover {

      background: rgba(181, 177, 177, 0.2);
}
#nav a:hover {

      background: rgba(181, 177, 177, 0.2);
}

#nav a.router-link-exact-active {
  color: #444;
  text-decoration: underline;
}
</style>
