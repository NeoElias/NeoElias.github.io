<template>
  <div id="mybio" class="columns">
    <div class="column">
      <h1 class="title is-1">{{ msg }}</h1>
      <h3>Software Developer</h3>
      <hr class="solid" />
      <p>I'm a passionate developer with a keen eye for details.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
#mybio {
  margin: 30vh;
  text-align: center;
  display: flex;
  justify-content: center;
  height: 40vh;
}

h1.title {
  margin-bottom: 4px;
  /* text-transform: uppercase; */
}

h3 {
  margin-top: 10px;
  text-transform: uppercase;
  font-size: 14px;
}
hr.solid {
  border-top: 2px solid black;
  width: 4rem;
  margin: 5px auto 30px;
}
</style>
