<template>
  <ScoreCounter name="Player 1" />
  <ScoreCounter name="Player 2" />
</template>

<script>
import ScoreCounter from "./components/ScoreCounter.vue";
export default {
  name: 'App',
  components: {
    ScoreCounter
  }
}
</script>

<style>
#app {
  font-family: sans-serif;
  font-size: 3rem;
  text-align: center;
}
</style>
