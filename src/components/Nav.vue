<template>
  <nav>
    <div class="title">
      <img src="https://pomofocus.io/icons/icon-white.png">
      <h1>Brenofocus</h1>
    </div>
    
    <router-link class="link" to="/">Home</router-link> 
  </nav>
</template>

<script>
export default {
}
</script>

<style scoped>
nav {
  display: flex;
  align-items: center; 
  justify-content: space-between;
  width: 600px;
  margin: auto;
  border-bottom: 1px solid #fff;
}

.title {
  display: flex;
  height: 50px;
  width: auto;
  align-items: center;
  justify-content: center;
  font-size: 14px;
}

.title img {
  height: 35%;
  margin-right: 5px;
}

.link {
  text-decoration: none;
  color: #fff;
  background: #ec9e9bcc;
  padding: 5px;
  border-radius: 3px;
  font-size: 13px;
}
</style>