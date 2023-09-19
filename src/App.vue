<template>
  <div class="container">
    <Header />
    <button>Add task</button>
  </div>
</template>

<script>
import Header from "./Header.vue";
export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style>
#app {
  text-align: center;
  color: yellowgreen;
  margin-top: 60px;
}
.container {
  border: 1px solid blue;
  padding: 20px;
  max-width: 500px;
  margin: auto;
}
button {
  padding: 10px 15px;
  background-color: darkgreen;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
</style>
