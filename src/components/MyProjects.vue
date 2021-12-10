<template>
  <div class="myprojects">
    <h1>Projects</h1>
    <div class="columns">
      <div class="column" v-for="project in projects" :key="project.name">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img :src="project.image" alt="BrewReview" />
            </figure>
          </div>
          <header class="card-header">
            <p class="card-header-title">{{ project.name }}</p>
          </header>
          <div class="card-content">
            <div class="content">
              <p>
                {{ project.description }}
              </p>
              <p>
                <mark><u>Technologies:</u></mark> {{ project.technologies }}
              </p>
            </div>
          </div>

          <footer class="card-footer">
            <a :href="project.url" class="card-footer-item" target="blank_"
              >Demo</a
            >
          </footer>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyProjects",
  data() {
    return {
      projects: [
        {
          name: "BrewReview",
          image:
            "https://project-images12.s3.us-east-2.amazonaws.com/brewreview.png",
          description:
            "Fullstack web app with authentication. User can create new favorite brewery pages and leave reviews",
          technologies: "Node.js, Express, MongoDB",
          url: "https://brewreviews.herokuapp.com/",
        },
        {
          name: "Data Collector",
          image:
            "https://project-images12.s3.us-east-2.amazonaws.com/datacollector.png",
          description:
            "Simple app that allows a user to enter demographic information to perform comparisons with other users",
          technologies: "Python, Flask, Bulma",
          url: "https://maraisanewebapps.pythonanywhere.com/",
        },
        {
          name: "Stock Analysis Visualization",
          image:
            "https://project-images12.s3.us-east-2.amazonaws.com/tesla-candlestick.png",
          description:
            "Market trend chart using Python and Bokeh library to display real-time stock data customized for the use",
          technologies: "Python, Bokeh,Pandas",
          url: "https://github.com/NeoElias/stockAnalysis_chart",
        },
      ],
    };
  },
};
</script>

<style scoped>
.myprojects {
  text-align: center;
  margin: 1.5rem 1.5rem;
  padding: 1.5rem;
}

h1 {
  text-align: center;
  font-size: 1.6rem;
  font-weight: bold;
  margin-bottom: 1.5rem;
}
.card-header-title {
  justify-content: center;
}
p {
  text-align: justify;
}
.card {
  box-shadow: 8px 14px 38px rgba(39, 44, 49, 0.06),
    1px 3px 8px rgba(39, 44, 49, 0.03);
  overflow: hidden;
  transition: all 0.5s ease;
}
.card:hover {
  transform: translate3d(0, -1px, 0) scale(1.03);
  box-shadow: 8px 28px 50px rgba(39, 44, 49, 0.07),
    1px 6px 12px rgba(39, 44, 49, 0.04);
  transition: all 0.4s ease; /* zoom in */
  cursor: pointer;
}
</style>
