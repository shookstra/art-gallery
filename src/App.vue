<template>
  <div id="app">
    <router-view class="body-container" />
    <Sidebar />
  </div>
</template>

<script>
import Sidebar from "./components/Sidebar";

export default {
  name: "Home",
  components: {
    Sidebar,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik&display=swap");

* {
  font-family: "Rubik", sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  display: flex;
  height: 100vh;
}

.body-container {
  /* border: 1px solid blue; */
  flex: 3;
  box-shadow: 5px 0px 10px 0px rgba(0, 0, 0, 0.15);
  z-index: 1;
  padding: 30px 15px 50px 15px;
  background-color: rgb(220, 220, 240);
}
</style>
