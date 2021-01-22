<template>
  <div id="app">
    <div id="nav">
      <router-link to="/" style="text-decoration:none;" class="click">首頁</router-link> |
      <router-link to="/about" style="text-decoration:none;" class="click">樂團簡介</router-link> |
      <router-link to="/member" style="text-decoration:none;" class="click">樂團成員</router-link> |
      <router-link to="/song" style="text-decoration:none;" class="click">樂團單曲</router-link> |
      <router-link to="/pic" style="text-decoration:none;" class="click">照片</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: "竹風體";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
	background-image: url('~@/assets/ss.gif');
  background-size: 250px;
	background-attachment: fixed;
  background-color: rgb(255, 255, 255, .6);
  background-blend-mode: lighten;
}

#nav {
  text-align: center;
  padding: 30px;
  font-size: 27px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #426cb9;
}

.click:hover {
		opacity: 0.6;
}
</style>
