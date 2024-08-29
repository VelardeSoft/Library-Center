<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'SideBar',
});
</script>

<template>
  <aside class="side-bar">
    <nav>
      <ul>
        <li class="btn">Books</li>
        <li class="btn">Authors</li>
        <li class="btn">Genres</li>
      </ul>
    </nav>
  </aside>
</template>

<style scoped>
.btn {
  cursor: pointer;
  background-color: #2c3e50;
  color: white;
  padding: 5px;
  margin-right: 150px;
  border-radius: 10px;
}
.btn:hover {
  background-color: aqua;
}
.side-bar {
  width: 250px;
  background-color: #513c86;
  padding: 10px;
  position: fixed;
  top: 60px;
  left: 0;
  height: 83%;
}
nav ul {
  list-style-type: none;
  padding: 0;
}
nav li {
  margin: 15px 0;
  color: white;
}
</style>