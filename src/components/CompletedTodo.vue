<template>
  <div>
      Completed Todo: {{ numberOfCompletedTodo }}
  </div>
</template>

<script>
export default {
    computed: {
        // todos() {
        //     return this.$store.state.todos;
        // },
        numberOfCompletedTodo() {
            return this.$store.getters['todo/numberOfCompletedTodo'];
        }
    }
}
</script>

<style>

</style>