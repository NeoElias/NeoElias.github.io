<template>
  <h1>About Me</h1>
  <div id="mystory" class="columns">
    <div class="column">
      <p>
        Highly coachable web developer with experience in JavaScript and Python.
        I have a passion for learning new technologies and have a demonstrated
        history of gaining new skills quickly throughout multiple previous
        roles. My background is in mechanical engineering with 4 years spent in
        product engineering collaborating with global teams at John Deere and
        Eaton. I enjoy solving challenging problems and working in a
        collaborative environment. I am seeking to solidify my professional
        software development skills and join an innovative, high-performing
        software team.
      </p>
    </div>
    <div class="column">
      <img alt="Profile Image" src="../assets/profile-pic.jpeg" />
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style scoped>
#mystory {
  margin: 40px;
}
h1 {
  text-align: center;
  font-size: 30px;
  font-weight: bold;
  margin-bottom: 20px;
  text-transform: uppercase;
}
</style>
