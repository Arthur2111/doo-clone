<template>
    <TopBar></TopBar>
    <NavigationBar></NavigationBar>


</template>

<script>
import TopBar from './components/TopBar.vue'
import NavigationBar from "./components/NavigationBar.vue";

export default {

  components: {
    TopBar,
    NavigationBar
  }
  
}


</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');


body{
  font-family: 'Poppins';
  padding: 0;
  margin: 0;
}
</style>
