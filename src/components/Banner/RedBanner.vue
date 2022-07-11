<template>
  <div class="container">
    <div class="banner">
      <h1>One Click Away To Global Investments <button class="register">Register</button></h1>
    </div>
  </div>
</template>


<style scoped>
.container{
  position: relative;

}

.banner {
  background-image: linear-gradient(to right, red, rgb(228, 68, 95));
  height: 10rem;
  width: 100%;
  margin-top: 8rem;
  display: flex;
  justify-content: center;
}

h1 {
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-size: 40px;
  margin-right: 10rem;
}


.register {
  position: absolute;
  padding: 1rem 3rem;
  border-radius: 10px;
  border: 2px solid red;
  font-size: 16px;
  display: flex;
  color: red;
  margin-left: 80rem;
}

.register:hover {
  position: absolute;
  padding: 1rem 3rem;
  border-radius: 10px;
  border: 2px solid red;
  font-size: 16px;
  display: flex;
  color: red;
  margin-left: 80rem;
  opacity: 0.8;
}


</style>