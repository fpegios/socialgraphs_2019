<template>
  <div id="network-analysis" class="overflow-hidden">
    <h1>Network Analysis</h1>
    
    <p>
      To analyze the data and find the connection between the drinks, we have created a network,
      in which the nodes represent the drinks. The drinks are connected to each other when they have a 
      common ingredients and the number of the shared ingredients define the weight of the connection.
      From this network, we can understand which drink categories use the most commonly used ingredients.
    </p>

    <div class="container">
      <div class="row">
        <div class="col-1"></div>
        <div class="col-10">
          <img :src="require('../assets/network.png')" class="img-fluid rounded">
        </div>
        <div class="col-1"></div>
      </div>
    </div>

    <p>
      As it can be seen ordinary drinks is the category that uses the most popular ingredients.
    </p>

  </div>
</template>

<script>
export default {
  name: 'NetworkAnalysis'
}
</script>

<style scoped>
</style>
