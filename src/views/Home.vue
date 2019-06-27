<template>
  <div class="home">
    <div>
      <div id="nav_follow">
        <a href="https://www.instagram.com/marwaneberiich/">Instagram</a>
        <a href="https://twitter.com/MarwaneBeriich/">Twitter</a>
        <a href="https://www.facebook.com/MarwaneBeriich">FaceBook</a>
        <a href="https://github.com/marwaneber/">GitHub</a>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
#nav_follow {
  margin: 30px;
  margin-top: 0;
  color: blue;
  border: 1px solid #0080FF;
  overflow: auto;
}

#nav_follow a {
  color: #0080FF;
  float: left;
  padding: 10px 0;
  width: 25%;
  box-sizing: border-box;
  display: inline;
  text-align: center;
}
</style>

