<template>
  <div class='ui centered card'>
    <div class='content'>
      <div class='ui form'>
        <div class='field'>
          <label>Title</label>
          <input type='text' value={this.state.title} onChange={this.handleTitleChange} />
            </div>
            <div class='field'>
              <label>Project</label>
              <input
                type='text'
                value={this.state.project}
                onChange={this.handleProjectChange}
              />
            </div>
            <div class='ui two bottom attached buttons'>
              <button
                class='ui basic blue button'
                onClick={this.handleSubmit}
              >
                {submitText}
              </button>
              <button
                class='ui basic red button'
                onClick={this.props.onFormClose}
              >
                Cancel
              </button>
            </div>
          </div>
        </div>
      </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
