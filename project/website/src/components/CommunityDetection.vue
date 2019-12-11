<template>
  <div id="community-detection" class="overflow-hidden">
    <h1>Community Detection</h1>
    
    <p>
      The following procedure is the community detection, wehere the network has been divided into
      clusters based on the ingredients are used in each drink. Below, we can see the wordclouds for each cluster.
    </p>

    <div class="container">
      <div class="row">
        <div class="col-4">
          <img :src="require('../assets/cd/c0.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-4">
          <img :src="require('../assets/cd/c1.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-4">
          <img :src="require('../assets/cd/c2.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
      <div class="row">
        <div class="col-4">
          <img :src="require('../assets/cd/c3.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-4">
          <img :src="require('../assets/cd/c4.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-4">
          <img :src="require('../assets/cd/c5.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
    </div>

    <p>
      Using this tool it can easily be understood which ingredients are used together in drinks. The outcome can be used to
      choose ingredients that when they are mixed, they offer tasty drinks.
    </p>

  </div>
</template>

<script>
export default {
  name: 'CommunityDetection'
}
</script>

<style scoped>
</style>
