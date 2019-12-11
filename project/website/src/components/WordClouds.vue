<template>
  <div id="wordclouds" class="overflow-hidden">
    <h1>WordClouds</h1>
    
    <p>
      In the last procedure, we have used wordclouds to visualize the most used keywords that exist in the recipe 
      instructions for each glass type and drink category. Moreover, we have also found which ingredients are mostly 
      used per drink category.
    </p>

    <h2>Instructions per Glass Type</h2>

    <div class="container">
      <div class="row">
        <div class="col-3 offset-1">
          <img :src="require('../assets/wa/wa_1.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wa/wa_2.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wa/wa_3.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
      <div class="row">
        <div class="col-3">
          <img :src="require('../assets/wa/wa_4.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wa/wa_5.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wa/wa_6.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wa/wa_7.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
    </div>
    <br>

    <h2>Instructions per Drink Category</h2>

    <div class="container">
      <div class="row">
        <div class="col-3">
          <img :src="require('../assets/wb/wb_1.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_2.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_3.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_4.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
      <div class="row">
        <div class="col-3">
          <img :src="require('../assets/wb/wb_5.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_6.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_7.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_8.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-3">
          <img :src="require('../assets/wb/wb_9.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_10.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wb/wb_11.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
    </div>
    <br>

    <h2>Ingredients per Drink Category</h2>

    <div class="container">
      <div class="row">
        <div class="col-3">
          <img :src="require('../assets/wc/wc_1.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_2.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_3.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_4.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
      <div class="row">
        <div class="col-3">
          <img :src="require('../assets/wc/wc_5.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_6.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_7.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_8.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-3">
          <img :src="require('../assets/wc/wc_9.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_10.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
        <div class="col-3">
          <img :src="require('../assets/wc/wc_11.png')" class="rounded img-fluid" alt="Dataset Sample">
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'WordClouds'
}
</script>

<style scoped>
</style>
