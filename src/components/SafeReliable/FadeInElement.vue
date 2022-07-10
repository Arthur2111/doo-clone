<template>
  <div class="container2">
    <div class="element-left">
      <a href="#" class="image-meta-trader">
        <img
          src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/MT4.svg"
          alt="MetaTrader4"
        />
        <div class="vl"></div>
        <h1>MetaTrader4</h1>
      </a>
      <h2>
        Enhance your trading experience with internationally recognized and
        reliable trading platforms.
        <div class="ho1"></div>
      </h2>
      <div class="download-links">
      <h2>
        Supported download platforms:
      </h2>
      <div class="grid-container">
        <div class="grid-element">
            <div class="grid-element-1">hello</div>
            <div class="grid-element-2">Ni hao</div>
        </div>
      </div>
      </div>
    </div>

    <div class="element-right">
      <img class="computer"
        src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/Doo-Prime-MT4.webp"
        alt="computer"
      />
    </div>
  </div>
</template>

<style scoped>

.container2{
    display: flex;
}


.image-meta-trader {
  display: flex;
  text-decoration: none;
}

.element-left {
  margin-top: 5rem;
}

.vl {
  border-left: 3px solid red;
  height: 50px;
  margin-left: 2rem;
  margin-top: 1rem;
}

.ho1 {
    border-bottom: 3px solid grey;
    opacity: 0.3;
    width: rem;
    margin-top: 5rem;
}

h1 {
  margin-left: 2rem;
  color: red;
}

h2 {
    font-size: 16px;
    margin-left: 8rem;
}

.computer{
    margin-right: 10rem;
}

.grid-container{
    margin-left: 8rem;
}


.grid-element{
    display: grid;
    grid-template-columns: 100px 100px;
}


</style>
