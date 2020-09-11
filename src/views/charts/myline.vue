<template>
  <div class="chart-container">
    <chart width="100%" height="100%" />
  </div>
</template>

<script>
import Chart from '@/components/Charts/MyLine'
export default {
  name: 'MyLine',
  components: { Chart }
}
</script>

<style scoped>
.chart-container{
  position: relative;
  width: 100%;
  height: calc(100vh - 84px);
}
</style>
