<template>
  <div id="dataset" class="overflow-hidden">
    <h1>Dataset</h1>
    
    <p>
      From Jerry Thomas and Gary Regan to the guy at the bar in our neighborhood, all bartenders worldwide mix 
      several and different ingredients with proper technique to finally serve us tasty drinks and make 
      the nights more beautiful. In this project, the analyzed dataset includes a list of the most popular alcoholic drinks. Each row of the datalist
      contains the category of the drink, the type of glass in which the drink is served, the used ingredients and the recipe instruction.
    </p>

    <p class="text-right">
      <a class="btn btn-primary" target="_blank" href="https://www.kaggle.com/ai-first/cocktail-ingredients/download" role="button">Download Dataset</a>
    </p>

    <div class="container">
      <div class="row">
        <div class="col overflow-auto">
          <img :src="require('../assets/dataset.png')" class="rounded">
        </div>
      </div>
    </div>
    <h6 class="text-center">Sample of the dataset</h6>
    <br>

    <p>The idea behind this analysis is to understand:</p>

    <ul>
      <li>How alcoholic drinks are connected to each other using <b>Network Analysis</b></li>
      <li>Which ingredients are mostly used together using <b>Community Detection</b> and <b>Wordclouds</b></li>
      <li>The most common instruction keywords per glass type and drink category using <b>Wordclouds</b></li>
      <li>And finally the most used ingredients per drink category using <b>WordClouds</b></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Dataset'
}
</script>

<style scoped>
</style>
