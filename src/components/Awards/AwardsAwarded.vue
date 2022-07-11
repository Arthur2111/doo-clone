<template>
    
<div class="top">
    <header><h1>Awards</h1></header>
    <h2>We pursue excellence, and strive to create the best trading commodity brand</h2>
    <div class="border-top"></div>
</div>

<award-image></award-image>



</template>


<script>
import AwardImage from "./AwardImage.vue"

export default {
    components: {
        AwardImage
    }
}
</script>

<style scoped>

h1{
    font-size: 50px;
}


h2{
    text-align: center;
    font-size: 15px;
}

.border-top {
  border-bottom: 1.5px solid grey;
  opacity: 0.2;
  margin-top: 5rem;
}



</style>