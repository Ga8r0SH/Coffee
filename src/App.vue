<template>
  <div>
    <Header/>
  </div>
</template>

<script>
import Header from './components/Header/Header.vue';
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
