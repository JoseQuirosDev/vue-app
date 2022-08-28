<template>
  <div class="container">
    <template>
      <ul>
        <RouterLink to="/"><li>Todo List</li></RouterLink>
        <RouterLink to="/new"><li>New Todo</li></RouterLink>
      </ul>
      <RouterView />
    </template>
  </div>
</template>


<script>

export default {
  name: 'App',

}
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
