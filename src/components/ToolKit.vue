<template>
  <h1>Technical Skills</h1>
  <div class="columns tool-kit">
    <div class="column">
      <h5 class="title is-5">Languages</h5>
      <ul>
        <li v-for="language in languages" :key="language.name">
          <img :src="language.icon" alt="language icon" />
          <p>{{ language.name }}</p>
        </li>
      </ul>
    </div>
    <div class="column">
      <h5 class="title is-5">Frameworks</h5>
      <ul>
        <li v-for="framework in frameworks" :key="framework.name">
          <img :src="framework.icon" alt="framework icon" />
          <p v-if="framework.name !== 'Flask' && framework.name !== 'Django'">
            {{ framework.name }}
          </p>
        </li>
      </ul>
    </div>
    <div class="column">
      <h5 class="title is-5">Platforms</h5>
      <ul>
        <li v-for="platform in platforms" :key="platform.name">
          <img :src="platform.icon" alt="platform icon" />
          <p>{{ platform.name }}</p>
        </li>
      </ul>
    </div>

    <div class="column">
      <h5 class="title is-5">Databases</h5>
      <ul>
        <li v-for="database in databases" :key="database.name">
          <img :src="database.icon" alt="database icon" />
          <p>{{ database.name }}</p>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "ToolKit",
  data() {
    return {
      languages: [
        {
          name: "Javascript",
          icon: "https://img.icons8.com/color/96/000000/javascript--v1.png",
        },
        {
          name: "Python",
          icon: "https://img.icons8.com/color/96/000000/python--v1.png",
        },
        {
          name: "HTML/CSS",
          icon: "https://img.icons8.com/color/96/000000/html-5--v1.png",
        },
        {
          name: "SCSS/SASS",
          icon: "https://img.icons8.com/color/96/000000/sass-avatar.png",
        },
      ],
      frameworks: [
        {
          name: "Vue.js",
          icon: "https://img.icons8.com/color/96/000000/vue-js.png",
        },
        {
          name: "Express",
          icon: "https://img.icons8.com/color/96/000000/express.png",
        },
        {
          name: "Flask",
          icon: "https://img.icons8.com/color/96/000000/flask.png",
        },
        {
          name: "Django",
          icon: "https://img.icons8.com/ios/100/000000/django.png",
        },
      ],
      platforms: [
        {
          name: "Node.js",
          icon: "https://img.icons8.com/fluency/96/000000/node-js.png",
        },
        { name: "Git", icon: "https://img.icons8.com/color/96/000000/git.png" },
        {
          name: "GitHub",
          icon: "https://img.icons8.com/material-sharp/96/000000/github.png",
        },
      ],
      databases: [
        {
          name: "MongoDB",
          icon: "https://img.icons8.com/color/96/000000/mongodb.png",
        },
        {
          name: "PostgreSQL",
          icon: "https://img.icons8.com/color/96/000000/postgreesql.png",
        },
      ],
    };
  },
};
</script>

<style scoped>
h1 {
  text-align: center;
  font-size: 1.6rem;
  font-weight: bold;
  margin-bottom: 20px;
}
.tool-kit {
  margin: 3rem;
}

img {
  width: 72px;
  height: 72px;
  vertical-align: middle;
}
ul {
  list-style-type: none;
}
ul li p {
  display: inline-block;
  vertical-align: middle;
}
ul li {
  margin: 5px;
}
</style>
