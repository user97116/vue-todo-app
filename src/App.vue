<template>
  <div id="app" class="container">
    <TodoInput />
    <TodoStatus />
    <TodoList />
  </div>
</template>

<script>
import TodoInput from "@/components/TodoInput";
import TodoList from "@/components/TodoList";
import TodoStatus from "@/components/TodoStatus";

export default {
  name: "App",
  components: {
    TodoInput,
    TodoList,
    TodoStatus
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
