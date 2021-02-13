<template>
  <div class="sidebar">
    <div id="nav">
      <h1 class="sidebar-title">Art Gallery</h1>
      <router-link to="/" class="sidebar-link">Home</router-link>
      <router-link to="/about" class="sidebar-link">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
};
</script>

<style scoped>
a {
  color: rgb(0, 0, 50);
  text-decoration: none;
}

.sidebar {
  background-color: #ffcad4;
  flex: 1;
}

.sidebar-title {
  padding-bottom: 30px;
}

.sidebar-link {
  padding: 15px;
  background-color: #f4acb7;
  /* color: white; */
  margin: 3px 0px;
  border-radius: 5px;
  transition: margin 250ms ease, box-shadow 250ms ease;
  font-size: 1.15rem;
  /* border: 1px solid blue; */
}

.sidebar-link:hover,
.sidebar-link:active,
.sidebar-link:focus {
  margin-left: 10px;
  box-shadow: 5px 3px 10px 0px rgba(0, 0, 0, 0.35);
}

#nav {
  /* background-color: red; */
  display: flex;
  flex-direction: column;
  padding: 100px 30px;
}
</style>
