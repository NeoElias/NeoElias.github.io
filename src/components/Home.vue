<template>
  <div id="mybio" class="columns reverse-columns">
    <div class="column is-two-fifths">
      <h1 class="title is-1">{{ msg }}</h1>
      <h3>Software Developer</h3>
      <hr class="solid" />
      <p>I'm a passionate developer with a keen eye to details</p>
    </div>

    <div class="column is-narrow">
      <img alt="Profile Image" src="../assets/profile-pic.jpeg" />
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
@media (max-width: 767px) {
  .reverse-columns {
    flex-direction: column-reverse;
    display: flex;
  }
}
#mybio {
  margin: 40px;
  margin-left: 90px;
  /* padding: 50px; */
  /* padding-right: 20px; */
}

img {
  border-radius: 293456px;
  /* margin-top: -50px; */
}
h1.title {
  margin-bottom: 4px;
  text-transform: uppercase;
}

h3 {
  text-transform: uppercase;
  font-size: 14px;
}
hr.solid {
  margin-top: 10px;
  border-top: 2px solid black;
  width: 4rem;
}
</style>
