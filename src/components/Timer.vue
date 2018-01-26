<template>
  <div class='ui centered card'>
        <div class='content'>
          <div class='header'>
            {{title}}
          </div>
          <div class='meta'>
            {{project}}
          </div>
          <div class='center aligned description'>
            <h2>{{elapsedString}}</h2>
          </div>
          <div class='extra content'>
            <span class='right floated edit icon'>
              <i class='edit icon' />
            </span>
            <span class='right floated trash icon' >
              <i class='trash icon' />
            </span>
          </div>
        </div>
        <TimerActionButton />
</template>

<script>
import TimerActionButton from './TimerActionButton.vue'
export default {
  name: "Timer"
};
</script>

<style>

</style>
