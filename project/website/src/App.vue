<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>

html, body, #app {
  height: 100%;
  overflow-x: hidden;
}

.tabs .card-header {
  position: fixed!important;
}

.tab-content {
  margin-left: 240px;
}

.tab-pane {
  height: 100%;
  padding-left: 10px!important;
  padding-right: 30px!important;
}

</style>
