<template>

<header class="container">
    <h1>Multiple Trading Accounts</h1>
</header>

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
    font-size: 20px;
}

a {
    display: flex;
    justify-content: center;
    text-decoration: none;
    color: red;
    font-size: 20px;
}


</style>