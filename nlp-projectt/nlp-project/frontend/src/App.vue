<template>
  <div class="main-container">
    <h1>Auto-complete System</h1>
    <Autocomplete />
    <p>Done By:</p>
    <p>Maymona Obaid 1190703</p>
    <p>Rama Abdalrahman 1191344</p>
    <p>Arwa Doha 1190324</p>
  </div>
</template>

<script>
import Autocomplete from './components/Autocomplete.vue'

export default {
  name: 'App',
  components: {
    Autocomplete
  }
}
</script>

<style>

  .main-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    font-family: 'Times', sans-serif;
  }

  h1 {
    font-size: 3rem;
  }
  p {
    text-align: center;
    font-family: 'Times', sans-serif;
  }

  @import url('https://fonts.googleapis.com/css2?family=Fredoka&display=swap');
</style>
