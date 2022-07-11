<template>
  <html>
      <div class="grid-container">
        <div class="grid-element">
          <div class="grid-element-one">
            <h1>Clients Worldwide</h1>
            
            <!-- counter element -->
            <div class="counter-container">
            <p class="counter">40,000 <span>+</span></p> 
            </div>

          </div>
          <div class="grid-element-two">
            <h1>Coverage Regions</h1>
            <p class="counter">40<span>+</span></p> 
          </div>
          <div class="grid-element-three">
            <h1>Institutional Partners</h1>
            <p class="counter">250 <span>+</span></p> 
          </div>
          <div class="grid-element-four">
            <h1>Elites from 10+ Cities</h1>
            <p class="counter">500 <span>+</span></p> 
          </div>
        </div>
      </div>
  </html>
</template>



<style scoped>



.grid-container {
  margin-top: 4rem;
}

.grid-element {
  display: grid;
  grid-template-columns: 20rem 20rem;
  grid-template-rows: 10rem 10rem;
}

h1 {
  font-size: 1rem;
  font-family: 'Poppins';
}

.counter-container {
    display: flex;
}

.counter {
    font-size: 3rem;
    color: red;
    font-weight: bold;
    margin-top: 0%;
}



</style>