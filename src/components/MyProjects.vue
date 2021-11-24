<template>
  <div class="myprojects">
    <h1>Projects</h1>
    <div class="columns">
      <div class="column">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">BrewReview</p>
            <button class="card-header-icon" aria-label="more options">
              <span class="icon">
                <i class="fas fa-angle-down" aria-hidden="true"></i>
              </span>
            </button>
          </header>
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="../assets/brewreview.png" alt="BrewReview" />
            </figure>
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
          <header class="card-header">
            <p class="card-header-title">Data Collector – Flask App</p>
            <button class="card-header-icon" aria-label="more options">
              <span class="icon">
                <i class="fas fa-angle-down" aria-hidden="true"></i>
              </span>
            </button>
          </header>
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="../assets/datacollector.png" alt="DataCollector" />
            </figure>
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
          <header class="card-header">
            <p class="card-header-title">Stock Analysis Visualization</p>
            <button class="card-header-icon" aria-label="more options">
              <span class="icon">
                <i class="fas fa-angle-down" aria-hidden="true"></i>
              </span>
            </button>
          </header>
          <div class="card-image">
            <figure class="image is-4by3">
              <img
                src="https://project-images12.s3.us-east-2.amazonaws.com/tesla-candlestick.png"
                alt="Stock Analysis Visualization"
              />
            </figure>
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
  margin: 20px;
  padding: 20px;
}

h1 {
  text-align: center;
  font-size: 30px;
  font-weight: bold;
  margin-bottom: 20px;
}
</style>
