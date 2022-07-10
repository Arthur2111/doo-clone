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
        <h2>Supported download platforms:</h2>
        <div class="grid-container">
          <div class="grid-element">
            <div class="grid-element-1">
              <img
                class="windows"
                src="../../assets/windows.png"
                width="50"
                height="50"
                alt="window-icon"
              />
              <h3>Windows Desktop</h3>
              <a href="#">
                <img
                  class="download"
                  src="../../assets/download.png"
                  height="20"
                  width="20"
                  alt="download-icon"
                />
              </a>
            </div>
            <div class="grid-element-2">
              <img
                class="windows"
                src="../../assets/Apple-Logo.png"
                width="90"
                height="50"
                alt="window-icon"
              />
              <h3>IOS Mobile</h3>
              <a href="#">
                <img
                  class="download"
                  src="../../assets/download.png"
                  height="20"
                  width="20"
                  alt="download-icon"
                />
              </a>
            </div>
            <div class="grid-element-3">
              <img
                class="windows"
                src="../../assets/google-play.png"
                width="50"
                height="50"
                alt="window-icon"
              />
              <h3>Windows Desktop</h3>
              <a href="#">
                <img
                  class="download"
                  src="../../assets/download.png"
                  height="20"
                  width="20"
                  alt="download-icon"
                />
              </a>
            </div>
            <div class="grid-element-4">
              <img
                class="windows"
                src="../../assets/android.png"
                width="50"
                height="50"
                alt="window-icon"
              />
              <h3>Windows Desktop</h3>
              <a href="#">
                <img
                  class="download"
                  src="../../assets/download.png"
                  height="20"
                  width="20"
                  alt="download-icon"
                />
              </a>
            </div>
          </div>
        </div>
        <div class="container3">
          <div class="metafive">
            <img
              src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/MT5.svg"
              alt="Meta5"
            />
            <a href="#"> MetaTrader5 </a>
          </div>
          <div class="dooprime">
            <img
              src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/DooPrimeInTrade.svg"
              alt="doo-prime-in-trade"
            />
            <a href="#">Doo Prime InTrade</a>
          </div>
          <div class="tradingview">
            <img
              src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/Tradingview.svg"
              alt="tradingview"
            />
            <a href="#">Trading View</a>
          </div>
        </div>
      </div>
    </div>

    <div class="element-right">
      <img
        class="computer"
        src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/homepage/Doo-Prime-MT4.webp"
        alt="computer"
      />
    </div>
  </div>
</template>

<style scoped>
.container2 {
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
  opacity: 0.2;
  margin-top: 5rem;
}

.ho2 {
  border-bottom: 3px solid grey;
  opacity: 0.2;
  width: 20rem;
  margin-top: 5rem;
  margin-right: 10rem;
  margin-bottom: 2rem;
}

h1 {
  margin-left: 2rem;
  color: red;
}

h2 {
  font-size: 16px;
  margin-left: 8rem;
}

h3 {
  display: flex;
  font-size: 0.7rem;
  padding-left: 2rem;
  padding-top: 1rem;
}

p {
  margin-left: 2rem;
  font-size: 2rem;
}

.computer {
  margin-right: 10rem;
}

.grid-container {
  margin-left: 8rem;
}

.grid-element {
  display: grid;
  grid-template-columns: 200px 200px;
  grid-template-rows: 100px 100px;
  grid-gap: 3rem;
}

.grid-element-1,
.grid-element-2,
.grid-element-3,
.grid-element-4 {
  display: flex;
}

.grid-element-4 {
  padding-left: 1rem;
}

img .android {
  padding-left: 0.5rem;
  margin-bottom: 1rem;
}

.grid-element-1 .download,
.grid-element-2 .download {
  margin-top: 1rem;
  margin-left: 2rem;
}

.grid-element-3 .download,
.grid-element-4 .download {
  margin-left: 2.8rem;
}

.container3 {
  display: block;
}

.metafive,
.dooprime,
.tradingview {
  display: flex;
}

.dooprime,
.tradingview {
  margin-top: 3rem;
}

.container3 a {
  text-decoration: none;
  color: black;
  margin-left: 2rem;
  display: flex;
  align-items: center;
  font-size: 30px;
  text-align: left;
}

.container3 a:hover{
  text-decoration: none;
  color: red;
  margin-left: 2rem;
  display: flex;
  align-items: center;
  font-size: 30px;
  text-align: left;
}


.element-right{
  display: flex;
  align-items: center;
}

</style>
