<template>
  <header>
    <Navbar />
  </header>
  <main>
    <router-view />
  </main>
  <footer class="container-fluid">
    <div class="row bg-dark p-4">
      <div class="col-8">
        <div class="row">
          <div class="col-12 p-4">
            Premium Reading Experience
          </div>
          <div class="col-12 bg-dark text-light text-center p-4 ">
            Site Ingredients: Love, Happiness, Truth, Creativity, Cowboys, Romance, Kissing, Heartstrings, Happily Ever Afters
          </div>

        </div>
      </div>
    <div class="col-4 pb-2 bg-success rounded">
      <div class="py-2"><span>Stolen Heart</span>      
        <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
      </div>
    </div>
      <div class="pb-2"><span>Christmas Novela</span>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 50%">50%</div>
      </div>
    </div>
      <div class="pb-2"><span>Night Train</span>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 30%">30%</div>
      </div>
    </div>
      <div class="pb-2"><span>Gemologist</span>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 3%">3%</div>
      </div>
    </div>
      <div class="pb-2"><span>Country By Charm</span>
      <div class="progress text-dark">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 0%">0%</div><span class="px-2"></span>0%
      </div>
    </div>
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
