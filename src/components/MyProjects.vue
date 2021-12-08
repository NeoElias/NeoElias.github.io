<template>
  <div class="myprojects">
    <h1>Projects</h1>
    <div class="columns">
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="../assets/brewreview.png" alt="BrewReview" />
            </figure>
          </div>
          <header class="card-header">
            <p class="card-header-title">BrewReview</p>
          </header>
          <div class="card-content">
            <div class="content">
              <p>
                Fullstack web app with authentication. User can create new
                favorite brewery pages and leave reviews
              </p>
              <p>
                <mark><u>Technologies:</u></mark> Node.js, Express, MongoDB
              </p>
            </div>
          </div>

          <footer class="card-footer">
            <a
              href="https://brewreviews.herokuapp.com/"
              class="card-footer-item"
              target="blank_"
              >Demo</a
            >
          </footer>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="../assets/datacollector.png" alt="DataCollector" />
            </figure>
          </div>
          <header class="card-header">
            <p class="card-header-title">Data Collector</p>
          </header>
          <div class="card-content">
            <div class="content">
              <p>
                Simple Flask app allowing a user to enter demographic
                information to perform comparisons with other users
              </p>
              <p>
                <mark><u>Technologies:</u></mark> Python, Flask,Bulma
              </p>
            </div>
          </div>
          <footer class="card-footer">
            <a
              href="https://maraisanewebapps.pythonanywhere.com/"
              class="card-footer-item"
              target="blank_"
              >Demo</a
            >
          </footer>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img
                src="https://project-images12.s3.us-east-2.amazonaws.com/tesla-candlestick.png"
                alt="Stock Analysis Visualization"
              />
            </figure>
          </div>
          <header class="card-header">
            <p class="card-header-title">Stock Analysis Visualization</p>
          </header>
          <div class="card-content">
            <div class="content">
              <p>
                Stock market trend chart using Python and Bokeh library to
                display real-time data customized for the user
              </p>
              <p>
                <mark><u>Technologies:</u></mark> Python, Bokeh,Pandas
              </p>
            </div>
          </div>
          <footer class="card-footer">
            <a
              href="https://github.com/NeoElias/stockAnalysis_chart"
              class="card-footer-item"
              target="blank_"
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
/* .content {
  margin-top: 1.5rem;
} */
</style>
