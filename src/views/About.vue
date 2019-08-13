<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p @click="name_it">
      Hey my name is
      <span>{{name}}</span>
    </p>
  </div>
</template>
<script>
export default {
  data: function() {
    return {
      name: "mr1"
    };
  },
  methods: {
    name_it: function() {
      var after = ["Marwane Beriich", "mr1", "mberiich", "marber", "Marwane", "bMarwane"];
      this.name = after[Math.random()*after.length|0];
      // var after = "MR1";
      // var full = "";
      // for (var l of after) {
      //   setTimeout(() => {}, 500);
      //   full += l;
      // }
      // return full;
    }
  }
};
</script>
