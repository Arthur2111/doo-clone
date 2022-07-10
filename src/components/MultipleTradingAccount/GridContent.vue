<template>
  <div class="containers">
    <div class="grid-content">
      <div class="grid-content-1">
        <img
          src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/CENT.svg"
          alt="Cent"
        />
        <h4>Account Currency: USC</h4>
      </div>
      <div class="grid-content-2">
        <img
          src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/STP.svg"
          alt="STP"
        />
        <h4>Account Currency: USD</h4>
      </div>
      <div class="grid-content-3">
        <img
          src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/ECN.svg"
          alt="ECN"
        />
        <h4>Account Currency: USD</h4>
      </div>
      <div class="grid-content-4">
        <h4>Minimum Deposit <span>100</span></h4>
      </div>
      <div class="grid-content-5">
        <h4>Minimum Deposit <span>100</span></h4>
      </div>
      <div class="grid-content-6">
        <h4>Minimum Deposit <span>5,000</span></h4>
      </div>
      <div class="grid-content-7">
        <h4>Spread <span class="row-3">High</span></h4>
      </div>
      <div class="grid-content-8">
        <h4>Spread <span class="row-3">Medium</span></h4>
      </div>
      <div class="grid-content-9">
        <h4>Spread <span class="row-3">High</span></h4>
      </div>
      <div class="grid-content-10">
        <h4>Free Demo <span class="row-4">None</span></h4>
        <br />
        <button class="register">Register</button>
      </div>
      <div class="grid-content-11">
        <h4>Free Demo <span class="row-4">Yes</span></h4>
        <br>
        <button class="register">Register</button>
      </div>
      <div class="grid-content-12">
        <h4>Free Demo <span class="row-4">Yes</span></h4>
        <br>
        <button class="register">Register</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.containers {
  margin-top: 7rem;
  margin-left: 15rem;
  background: white;
}
.grid-content {
  display: grid;
  grid-template-columns: 30rem 30rem 30rem;
  grid-template-rows: 8rem 8rem 8rem 8rem;
  justify-content: center;
  align-items: center;
  grid-gap: 1rem;
  text-align: left;
}

h4 {
  font-size: 1rem;
  text-align: left;
}

span {
  margin-left: 3rem;
  font-size: 2rem;
  font-weight: none;
}

.row-3 {
  margin-left: 8rem;
}

.row-4 {
  margin-left: 6.3rem;
}

.register {
  padding: 1rem 3rem;
  border-radius: 10px;
  border: 1.5px solid red;
  font-size: 16px;
  display: flex;
  margin-left: 4rem;
}

.register:hover {
  padding: 1rem 3rem;
  border-radius: 10px;
  border: 1.5px solid red;
  font-size: 16px;
  display: flex;
  margin-left: 4rem;
  background: red;
  color: white;
}

</style>
