<template>
  <div>
    <h1>Home View</h1>
    <ExampleComponent />
  </div>
</template>

<script>
import ExampleComponent from '../components/ExampleComponent.vue';

export default {
  name: 'Home',
  components: {
    ExampleComponent,
  },
};
</script>

<style scoped>
/* Add styles for Home view */
</style>