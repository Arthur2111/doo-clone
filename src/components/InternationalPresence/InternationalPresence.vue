<template>

<div class="container">
    <div class="background-gif">
        <img src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/earth.gif" alt="world-gif">
    </div>

    <div class="element-right">
        <div class="top-text">
            <h1>International Presence</h1>
            <h2>There are operation centers in Dallas, Sydney, Singapore, Hong Kong, Dubai, Kuala Lumpur and other places.</h2>
        </div>
        <counter-element></counter-element>
    </div>

    



</div>



</template>


<script>
import CounterElement from "./CounterElement.vue"

export default {
    components:{
        CounterElement
    }


}
</script>


<style scoped>

.container{
    position: relative;
    background-color: #f8f9fa;
    display: flex;
    align-items: center;
}

.background-gif {
    margin-left: 3rem;
}

.element-right {

}

.element-right .top {
    display: block;
    align-items: center;
}

h1 {
    font-size: 40px ;
}

h2 {
    font-size: 12px ;
}



</style>