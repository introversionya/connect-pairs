<template>
  <div class="app">
    <img
      class="logo"
      alt="Vue logo"
      src="./assets/logo.png"
    />
    <Board />
  </div>
</template>

<script>
import Board from '@/components/Board.vue';

export default {
  name: 'App',
  components: {
    Board,
  },
  data() {
    return {
      cells: 16,
    };
  },
};
</script>

<style>
.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.logo {
  width: 100px;
}
</style>
