<template>
  <div id="app">
    <div>
      <TodoHeader></TodoHeader>
      <TodoInput></TodoInput>
      <TodoList></TodoList>
      <TodoFooter></TodoFooter>
    </div>
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader.vue'
import TodoInput from './components/TodoInput.vue'
import TodoList from './components/TodoList.vue'
import TodoFooter from './components/TodoFooter.vue'

export default {

  components : {
    // 컴포넌트 태그명 : 컴포넌트 내용
    TodoHeader,
    TodoInput,
    TodoList,
    TodoFooter
  }
}
</script>

<style>
body {
  text-align: center;
  background-color: #f6f6f6;
}

input {
  border-style: groove;
  width : 200px;
}

button {
  border-style: groove;
}
.shadow {
  box-shadow: 5px, 10px 10px rgba(0, 0, 0, 0.83);
}
</style>
