<script setup>
</script>

<template>
  <div class="container">
    <div class="content">
      <h1 class="title">Login</h1>
      <form class="forms">
        <input class="input" type="text" placeholder="Name">
        <input class="input" type="text" placeholder="E-mail">
        <button type="submit">LOGIN</button>
      </form>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 750px;
  background-image: url('../public/login.jpg');
  background-repeat: no-repeat;
  background-size: cover;
}
.content {
  display: flex;
  flex-direction: column;
  align-items: center;  
  width: 350px;
  height: 500px;
  background: linear-gradient(180deg, #19191b 15%, #2f2f2f 55%, #808080 95%);
  opacity: 80%;
}

.title {
  margin-top: 30px;
  font-weight: bold;  
  color: aliceblue;
}

.forms {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 110px;
}

.input {
  width: 250px;
  height: 35px;
  margin-bottom: 40px;
  padding-left: 5px;
  background-color: #9a9595;
  border: none;
}

.input::placeholder {
  color: #2d2d2f;
}

button {
  width: 100px;
  height: 35px;
  margin-top: 20px;
  padding-top: 2px;
  font-size: 20px;
  font-weight: bold;
  background-color: #19191b;
  color: aliceblue;
}
</style>
