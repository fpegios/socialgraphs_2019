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
  margin-left: 220px;
}

.tab-pane {
  padding-left: 50px!important;
  padding-right: 50px!important;
}

.img-fluid {
  /* max-width: 70%!important; */
}

</style>
