<template>
  <b-container class="p-0 h-100" fluid>
    <b-row class="h-100" no-gutters>
      <b-col>
        <b-tabs class="h-100" pills card vertical align="center">
          <b-tab title="Dataset" active>
            <Dataset />
          </b-tab>
          <b-tab title="Analysis">
            <Analysis />
          </b-tab>
          <b-tab title="Community Detection">
            <CommunityDetection />
          </b-tab>
        </b-tabs>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import Dataset from './Dataset.vue'
import Analysis from './Analysis.vue'
import CommunityDetection from './CommunityDetection.vue'

export default {
  name: 'Index',
  components: {
    Dataset,
    Analysis,
    CommunityDetection
  }
}
</script>

<style scoped>

</style>
