<template>
  <header>
    <h1>{{title}}</h1>
    <Button text="Add task" color="green"></Button>
    <Button text="Update task" color="blue"></Button>
    <Button text="Delete task" color="red"></Button>
  </header>
</template>

<script>
import Button from './Button'
export default {
  name: "Header",
  components: {
    Button
  },
  props: {
    title: String
  }
}
</script>

<style scoped>
  header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
  }
</style>
