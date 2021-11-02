<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="https://neoelias.github.io">
        <img src="../assets/nm-logo.png" width="85" height="43" />
      </a>

      <a
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="nav-menu"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="nav-menu" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item"> About Me </a>
        <a class="navbar-item"> Projects </a>
        <a class="navbar-item"> Contact </a>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="field is-grouped">
            <p class="control">
              <a
                class="button"
                target="_blank"
                href="https://github.com/NeoElias"
              >
                <span class="icon">
                  <font-awesome-icon :icon="['fab', 'github']" />
                </span>
              </a>
            </p>
            <p class="control">
              <a
                class="button"
                target="_blank"
                href="https:/linkedin.com/in/neom15"
              >
                <span class="icon">
                  <font-awesome-icon :icon="['fab', 'linkedin']" />
                </span>
              </a>
            </p>
            <p class="control">
              <a
                class="button is-info"
                href="https://myvueprojectfiles.s3.us-east-2.amazonaws.com/NeoMaraisaneResume.pdf"
                target="blank_"
              >
                <span class="icon">
                  <font-awesome-icon :icon="['fas', 'file-download']" />
                </span>
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
document.addEventListener("DOMContentLoaded", () => {
  // Get all "navbar-burger" elements
  const $navbarBurgers = Array.prototype.slice.call(
    document.querySelectorAll(".navbar-burger"),
    0
  );

  // Check if there are any navbar burgers
  if ($navbarBurgers.length > 0) {
    // Add a click event on each of them
    $navbarBurgers.forEach((el) => {
      el.addEventListener("click", () => {
        // Get the target from the "data-target" attribute
        const target = el.dataset.target;
        const $target = document.getElementById(target);

        // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
        el.classList.toggle("is-active");
        $target.classList.toggle("is-active");
      });
    });
  }
});

export default {
  name: "NavBar",
};
</script>

<style scoped>
.navbar {
  background-color: aquamarine;
  margin-bottom: 20px;
}

li {
  list-style-type: none;
}

.navbar-brand {
  padding-right: 30px;
  font-size: 40px;
  font-weight: bold;
}

.svg-inline--fa {
  width: 30px;
  height: 30px;
}
</style>
