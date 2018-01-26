<template>
  <div v-if="timerIsRunning" class='ui bottom attached red basic button'>Stop</div>
  <div v-else class='ui bottom attached green basic button'>Start</div>
</template>

<script>
export default {
  name: 'TimerActionButton',
  props: [timerIsRunning],
  methods: []
}
</script>

<style>

</style>
