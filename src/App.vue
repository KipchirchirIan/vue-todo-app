<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <TodoApp></TodoApp>
  </div>
</template>

<script>
import TodoApp from "@/components/TodoApp";
export default {
  name: "App",
  components: {
    TodoApp,
  },
};
</script>

<style></style>
