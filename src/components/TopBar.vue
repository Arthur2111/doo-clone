<template>
 <div class="navbar">
  <div class="dropdown">
    <button class="dropbtn">Language 
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <a href="#">English</a>
        <a href="#">简体中文</a>
        <a href="#">繁體中文</a>
        <a href="#">日本語</a>
        <a href="#">한국어</a>
        <a href="#">ไทย</a>
        <a href="#">Tiếng Việt</a>
    </div>
  </div> 
  <a href="#home">Free Demo</a>

</div>

  <NavigationBar></NavigationBar>


</template>



<script>


import NavigationBar from "./NavigationBar.vue";

export default {
  components: {
    NavigationBar,
  },
};

</script>




<style scoped>

body {
  font-family: Arial, Helvetica, sans-serif;
}

.navbar {
  overflow: hidden;
  background-color: #131721;
}

.navbar a {
  float: right;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.dropdown {
  float: right;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.navbar a:hover {
  background-color: #131721;
  color: red;
}

.dropdown:hover .dropbtn {
  background-color: #000018;
  color: red;
}


.dropdown-content {
  display: none;
  position: absolute;
  color: white;
  background-color: #000018;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #000018;
  color: #d91d22;
}

.dropdown:hover .dropdown-content {
  display: block;
}

</style>
