<template>
  <h1>About Neo</h1>
  <div id="mystory" class="columns">
    <div class="column">
      <p>
        Highly coachable web developer with experience in JavaScript and Python.
        I have a passion for learning new technologies and have a demonstrated
        history of gaining new skills quickly throughout multiple previous
        roles.
        <br />
        <br />
        My background is in mechanical engineering with 4 years spent in product
        engineering collaborating with global teams at John Deere and Eaton. I
        enjoy solving challenging problems and working in a collaborative
        environment. I am seeking to solidify my professional software
        development skills and join an innovative, high-performing software
        team.
      </p>
    </div>
    <div class="column image-container">
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
  margin: 2rem 6.5rem;
}
h1 {
  font-size: 1.6rem;
  font-weight: bold;
  margin-left: 2.4rem;
}
p {
  font-size: 1.1rem;
}
img {
  border-radius: 12px;
  max-height: 239px;
  max-width: 239px;
}

.image-container {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}
@media only screen and (max-width: 600px) {
  #mystory {
    margin: 1.5rem 1.5rem;
  }
}
@media only screen and (min-width: 768px) {
  #mystory {
    margin: 1.5rem 1.5rem;
  }
}
</style>
