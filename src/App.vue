<template>
  <div id="app">
    <Nav />
    <Menu />
    <div class="main-content">
      <router-view/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from '@/components/elements/Nav.vue';
import Menu from '@/components/elements/Menu.vue';

export default {
  name: 'App',
  components: {
    Nav,
    Menu,
  },
};
</script>

<style lang="scss">
@import '@/styles/index.scss';
</style>
