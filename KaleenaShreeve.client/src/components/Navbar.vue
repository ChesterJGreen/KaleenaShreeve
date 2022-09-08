<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-info px-3">
    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
      <div class="d-flex flex-column align-items-center">
      </div>
      <div>
        <h3 class="px-3">Kaleena Shreeve:</h3>
        <h5 class="px-3">Publishing Happiness</h5>
      </div>
    </router-link>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">
        <li>
          <router-link
            :to="{ name: 'About' }"
            class="btn text-success lighten-30 selectable text-uppercase"
          >
            About Me
          </router-link>
          <router-link
            :to="{ name: 'Books&Art' }"
            class="btn text-success lighten-30 selectable text-uppercase"
          >
            Books & Art
          </router-link>
          <router-link
            :to="{ name: 'Blog' }"
            class="btn text-success lighten-30 selectable text-uppercase"
          >
            Blog
          </router-link>
          <router-link
            :to="{ name: 'Contact' }"
            class="btn text-success lighten-30 selectable text-uppercase"
          >
            Contact
          </router-link>
        </li>
      </ul>
      <!-- LOGIN COMPONENT HERE -->
      <Login />
    </div>
  </nav>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped>
a:hover {
  text-decoration: none;
}
.nav-link {
  text-transform: uppercase;
}
.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
</style>
