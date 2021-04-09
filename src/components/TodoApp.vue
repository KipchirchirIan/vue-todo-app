<template>
  <div>
    <div v-for="(todo, index) in todos" :key="index">
      {{ todo }}
    </div>
  </div>
</template>

<script>
export default {
  name: "TodoApp",
  data: function () {
    return {
      todos: ["Learn Vue", "Learn Laravel", "Build a LaraVue project"],
      completedTodos: [],
    };
  },
};
</script>

<style scoped></style>
