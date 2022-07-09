<template>
  <header>
    <h2>Top-Notch Trading Environment</h2>
  </header>
    <h3>Enjoy Profitable Returns on Global Investment Transactions</h3>
    <br>

    <grid-element></grid-element>

</template>


<script>
import GridElement from "./GridElement.vue"


export default {
    components: {
        GridElement
    }
};
</script>

<style>

header {
    display: flex;
    font-size: 2rem;
    line-height: 64px;
    margin-bottom: 0;
    justify-content: center;
}

h3 {
    display: flex;
    justify-content: center;
    font-size: 1rem;
    padding: 0;
    margin: 0;
    top: 0;
}



</style>
