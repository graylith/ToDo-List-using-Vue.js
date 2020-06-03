<template>
  <div id="app">
    <div class="container">
      <AddTodo/>
      <filterTodos/>
      <Todos/>
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos.vue';
import AddTodo from'./components/addTodo';
import filterTodos from './components/filterTodo';
export default {
  name: 'App',
  components: {
    Todos,
    AddTodo, 
    filterTodos
  }
}
</script>

<style>
body{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  line-height: 1.6;
  background: #c3ecd9;
}
.container{
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
