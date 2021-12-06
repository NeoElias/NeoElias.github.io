<template>
  <div id="mybio" class="columns">
    <div class="column">
      <p>Good afternoon &#128075; &nbsp;&nbsp;&nbsp;My name is</p>
      <h1 class="title is-1">{{ msg }}</h1>

      <p class="dynamic-bio">
        I'm a passionate developer with a keen eye for details.
      </p>
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
  padding-top: 30vh;
  display: flex;
  height: 100vh;
  padding-left: 7rem;
}
@media only screen and (max-width: 600px) {
  #mybio {
    padding-top: 30vh;
    margin: auto;
    height: 100vh;
  }
}

@media only screen and (min-width: 768px) {
  #mybio {
    padding-top: 30vh;
    margin: auto;
    height: 100vh;
  }
}
h1.title {
  margin-bottom: 0.8rem;
  margin-left: 1.6rem;
  font-size: 80px;
}

hr.solid {
  margin-top: 0.2rem;
  margin-left: 2.5rem;
  border-top: 2px solid black;
  width: 4rem;
}
p {
  font-size: 20px;
}
.dynamic-bio {
  margin-left: 3.8rem;
}
</style>
