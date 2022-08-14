<template>
  <div class="container">
    <HeaderComponent />
    <TestComponent />
  </div>
</template>

<script>
import TestComponent from './components/TestComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    TestComponent
}
}
</script>

<style>
#app {
  border: 1px solid black;
}
</style>
