<template>

<div class="container">
    <h1>Multiple Trading Accounts</h1>
</div>

<a href="#">Learn More</a>

<grid-content></grid-content>



</template>


<script>
import GridContent from "./GridContent.vue"


export default{
    components: {
        GridContent
    }
}

</script>


<style scoped>


.container{
    display: flex;
    justify-content: center;
    margin-top: 2rem;
}

a {
    display: flex;
    justify-content: center;
    text-decoration: none;
    color: red;
}


</style>