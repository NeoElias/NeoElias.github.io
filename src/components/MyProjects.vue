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
              <img src="../assets/template.png" alt="Placeholder image" />
            </figure>
          </div>
          <footer class="card-footer">
            <a href="#" class="card-footer-item">Demo</a>
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
              <img src="../assets/template.png" alt="Placeholder image" />
            </figure>
          </div>
          <footer class="card-footer">
            <a href="#" class="card-footer-item">Demo</a>
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
              <img src="../assets/template.png" alt="Placeholder image" />
            </figure>
          </div>
          <footer class="card-footer">
            <a href="#" class="card-footer-item">Demo</a>
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
  text-transform: uppercase;
}
</style>
