<template>
  <div id="app">
    <app-button id="red" @click="log">
      <hart-icon />
      add to favorites
    </app-button>
  </div>
</template>

<script>
import AppButton from './components/AppButton.vue';
import HartIcon from './components/HartIcon.vue';

export default {
  components: {
    AppButton,
    HartIcon,
  },
  methods: {
    log() {
      console.log('works');
    },
  },
};
</script>

<style>
#app {
  font-family: sans-serif;
}
</style>
