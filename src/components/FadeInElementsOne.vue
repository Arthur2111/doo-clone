<template>
<div class="container">
    <!-- use keyframes rule  -->
    <div class="element-left">
        <h1>Flexible Fund Access</h1>
        <h2><span>22</span> Currencies Supported</h2>
        <h2><span>20</span> Funding Methods Available</h2>
        <div class="grid-left-row-1">
            <img class="visa" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/VISA.svg" alt="Visa">
            <img class="mastercard" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/mastercard.svg" alt="MasterCard">
        </div>
        <div class="grid-left-row-2">
            <img class="skrill" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/skrill.svg" alt="Skrill">
            <img class="neteller" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/neteller.svg" alt="Neteller">
        </div>
        <div class="grid-left-row-3">
            <img class="epay" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/epay.svg" alt="Epay">
        </div>


    </div>


    <div class="element-right">

        <img src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/Doo-Prime-e-Wallet.webp" alt="hand-phone">
        <img class="band-aid" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/element2.svg" alt="bandage">
        <img class="band-aid-two" src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/homepage-element.svg" alt="bandage">

    </div>
</div>


</template>

<style scoped>

h1 {
    font-size: 2rem;
    text-align: left;
}

h2 {
    font-size: 1rem;
    text-align: left;
}

span {
    font-size: 2rem;
    color: #d91d22;
}

.container{
    display: flex;
    justify-content: center;
    text-align: center;
}

.element-left{
    padding-right: 15rem;
    transition: all 0.3s ease;
}

.grid-left-row-1,
.grid-left-row-2,
.grid-left-row-3{
    display: flex;
    margin-top: 3rem;
    justify-content: space-between;
}
.neteller{
    margin-left: 2rem;
}

.element-right{
    position: relative;
}

.container .element-right .band-aid{
    z-index: 800;
    position: absolute;
    right: -15rem;

}
.container .element-right .band-aid-two{
    z-index: 820;
    position: absolute;
    bottom: -4rem;
    right: 20rem;
}



</style>


