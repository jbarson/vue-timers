<template>
    <div class='ui three column centered grid'>
        <div class='column'>
          <EditableTimerList
            timers={this.state.timers}
            onFormSubmit={this.handleEditFormSubmit}
            onTrashClick={this.handleTrashClick}
            onStartClick={this.handleStartClick}
            onStopClick={this.handleStopClick}
          />
          <ToggleableTimerForm
            onFormSubmit={this.handleCreateFormSubmit}
          />
        </div>
      </div>
</template>

<script>
import ToggleableTimerForm from './ToggleableTimerForm.vue'
import EditableTimerList from './EditableTimerList.vue'
export default {
  name: 'TimersDashboard',
  data: {
    timers: [
      {
        "title": "Clear paper jam",
        "project": "Office Chores",
        "elapsed": 1273998,
        "id": "a73c1d19-f32d-4aff-b470-cea4e792406a",
        "runningSince": null
      },
      {
        "title": "Ponder origins of universe",
        "project": "Life Chores",
        "id": "2c43306e-5b44-4ff8-8753-33c35adbd06f",
        "elapsed": 40815205370,
        "runningSince": null
      },
      {
        "title": "Mow the lawn",
        "project": "Home Chores",
        "id": "a30ec1cd-b4c7-41bd-b882-8f5b3a88fa3b",
        "elapsed": 7723,
        "runningSince": null
      }
    ]
  },
};
</script>

<style>

</style>
