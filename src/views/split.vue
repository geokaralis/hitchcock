<template>
  <main class="layout-split-view">
    <titlebar title="Popcorn"/>
    <sidebar/>
    <content-view/>
  </main>
</template>

<script>
import Titlebar from './titlebar';
import Sidebar from './sidebar';
import ContentView from './content';

export default {
  name: 'split-view',
  components: {
    Sidebar,
    ContentView,
    Titlebar
  }
}
</script>

<style scoped>
.layout-split-view {
  height: 100%;
  display: flex;
  overflow: hidden;
}
</style>

