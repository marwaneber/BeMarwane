<template>
  <div id="app">
    <div id="nav">
      <img alt="Vue logo" :src="require('@/assets/logo.png')">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
    <div id="footer">
      <router-link to="/">Marwane Beriich</router-link> &copy; 2019
    </div>
  </div>
</template>

<style>
body {
  margin: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0;
}
#nav {
  padding: 30px;
  height: 40px;
  margin-bottom: 30px;
  background: linear-gradient(90deg, #2196F3, #00BCD4);
}

#nav img {
  height: 100%;
  float: left;
}

#nav a {
  font-weight: bold;
  color: white;
  padding: 10px;
  float: right;
  text-decoration: none;
}
a:hover {
  background: rgba(181, 177, 177, 0.2);
}
#nav a:hover {
  background: rgba(181, 177, 177, 0.2);
}

#nav a.router-link-exact-active { a
  color: #444;
  text-decoration: underline;
}
#footer {
  padding: 30px;
  height: 40px;
  text-align: center;
  color: white;
  background: linear-gradient(-90deg, #2196F3, #00BCD4);
  position:sticky;
  bottom: 0;
}

#footer a {
  color: inherit;
  margin: 0;
  padding: 0;line-height: 40px;
}
</style>
