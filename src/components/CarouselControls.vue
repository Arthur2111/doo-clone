<template>
    <button class="carousel-control left"  @click="$emit('prev')" >Prev</button>
    <button class="carousel-control right " @click="$emit('next')" >Next</button>
</template>



<script>

export default {

    // buttons will emit to parent component the prev and next methods
    emits: ['prev', 'next']
}


</script>


<style scoped>

.carousel-control {
    background-color: rgba(0, 0, 0, .5);
    border: none;
    display: inline-block;
    position: absolute;
    height: 50px;
    width: 70px;
    top: calc(70% - 120px);
    color: #f3f3f3;
    cursor: pointer;

}

.left{
    left: 0;
}

.right {
    right: 0;
}


</style>