<template>
  <b-container class="p-0 h-100" fluid>
    <b-row class="h-100" no-gutters>
      <b-col>
        <b-tabs class="h-100" pills card vertical align="center">
          <b-tab title="Introduction" active>
            <Introduction />
          </b-tab>
          <b-tab title="Dataset">
            <Dataset />
          </b-tab>
          <b-tab title="Network Analysis">
            <NetworkAnalysis />
          </b-tab>
          <b-tab title="Conclusion">
            <Conclusion />
          </b-tab>
        </b-tabs>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import Introduction from './Introduction.vue'
import Dataset from './Dataset.vue'
import NetworkAnalysis from './NetworkAnalysis.vue'
import Conclusion from './Conclusion.vue'

export default {
  name: 'Index',
  components: {
    Introduction,
    Dataset,
    NetworkAnalysis,
    Conclusion
  },
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>
