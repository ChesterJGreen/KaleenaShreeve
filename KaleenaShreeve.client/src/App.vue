<template>
  <header>
    <Navbar />
  </header>
  <main>
    <router-view />
  </main>
  <footer class="container-fluid">
    <div class="row bg-dark">
      <div class="col-8">
        <div class="row">
          <div class="col-12 p-4">
            Premium Reading Experience
          </div>
          <div class="col-12 bg-dark text-light text-center p-4">
            Site Ingredients: Love, Happiness, Truth, Creativity, Cowboys, Romance, Kissing, Heartstrings, Happily Ever Afters
          </div>

        </div>
      </div>
    <div class="col-4">

    </div>
    </div>
  </footer>
</template>

<script>
import { computed } from 'vue';
import { AppState } from './AppState';

export default {
  name: 'App',
  setup() {
    return {
      appState: computed(() => AppState)
    }
  }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";
</style>
