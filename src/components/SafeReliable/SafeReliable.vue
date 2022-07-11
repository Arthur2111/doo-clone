<template>
<div class="container">
    <div class="header">
        <h2>Safe and Reliable Trading Platforms</h2>
    </div>
    <div class="subtext">
        <h2>Enhance your trading experience with internationally recognized and reliable trading platforms.</h2>
    </div>
    <fade-in-element></fade-in-element>
</div>



</template>

<script>
import FadeInElement from "./FadeInElement.vue"

export default {
    components: {
        FadeInElement
    }
}


</script>


<style scoped>



.container{
    margin-top: 10rem;
    margin-left: 20rem;
}

.header{
    text-align: left;
    display: flex;
}

.subtext{
    font-size: 8px;
    text-align: left;
}


</style>