<template>
  <div id="main" class="main ui">
    <h1 class="ui dividing centered header">Timers</h1>
    <div id="app" class="ui three column centered grid"></div>
  </div>

</template>

<script>
import TimersDashboard from "./TimersDashboard.vue";
export default {
  name: 'app',
  data () {
    return {

    }
  }
}
</script>

<style>
#main {
  margin-top: 6em;
}

#content {
  margin-top: 3em;
}

</style>
