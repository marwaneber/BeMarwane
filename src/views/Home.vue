<template>
  <div class="home">
    <div>
      <div id="nav_follow">
        <a href="https://www.instagram.com/marwaneberiich/">Instagram</a>
        <a href="https://twitter.com/MarwaneBeriich/">Twitter</a>
        <a href="https://www.facebook.com/MarwaneBeriich">FaceBook</a>
        <a href="https://github.com/marwaneber/">GitHub</a>
      </div>
      <div id="layout">
        <h2 id="headline">Projects</h2>
        <div id="part" v-for="i in [1, 2, 3, 4, 5, 6]" :key="i">
          <h3>Test project</h3>
          <p>Here is a simple description about this small project.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
/* eslint-disable */

// @ is an alias to /src

export default {
  name: "home"
};
</script>

<style scoped>
#nav_follow {
  margin: 30px;
  margin-top: 0;
  color: blue;
  border: 1px solid #0080ff;
  overflow: auto;
}

#nav_follow a {
  color: #0080ff;
  float: left;
  padding: 10px 0;
  width: 25%;
  box-sizing: border-box;
  display: inline;
  text-align: center;
}

#layout {
  margin: 30px;
  margin-top: 0;
}

#layout #headline, #part {
  border: 1px solid #0080ff;
  margin: 30px 0;
  margin-top: 0;
  padding: 0 20px;
}

#layout #part h3, p {
  text-align: left;
}
</style>
