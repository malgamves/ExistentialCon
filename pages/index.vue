<template>
  <div>
    <div id="main">
      <div id="screen">
        <div class="top"></div>
        <div class="bottom"></div>
        <div class="left"></div>
        <div class="right"></div>
        <div id="">
          <div class="text">
            <div class="top-message">join us at</div>
            <div class="error-code">Existential</div>
            <div class="erroe-code">con</div>
            <div class="error-message">
                <span><nuxt-link class="sub-link" to="/speakers">speakers</nuxt-link></span>|<span><nuxt-link class="sub-link" to="/about">about us </nuxt-link></span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Rubik+Mono+One');

* {
    box-sizing: border-box;
}

.sub-link:hover {
    text-decoration: underline;
    text-decoration-style: double;
}

#main {
    background: black;
    padding: 8rem 2rem;
    min-height: 100vh;
}

#screen {
    width: calc(80 * 1vw);
    height: calc(60 * 1vw);
    max-width: 800px;
    max-height: 600px;
    margin: 0 auto;
    position: relative;
    top: 10%;
}

.top, .bottom {
    background: white;
    border-radius: 50%;
    height: 20%;
    position: absolute;
    width: 100%;
    box-shadow: 0 0 3rem #eee;
}

.left, .right {
    background: white;
    border-radius: 50%;
    width: 10%;
    position: absolute;
    top: -1%;
    bottom: -1%;
    box-shadow: 0 0 3rem #eee;
}

.top {
    top: -10%;
}

.bottom {
    bottom: -10%;
}

.left {
    left: -4.5%;
}

.right {
    right: -4.5%;
}


.text {
    background: white ;
    position: absolute;
    top: 2.5%;
    bottom: 2.5%;
    left: 2.5%;
    right: 2.5%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    font-size: 175%;
    font-weight: normal;
    font-family: 'Rubik Mono One', sans-serif;
    text-align: center;
    text-shadow: 0 0 8px #888;
  
.error-code {
    font-size: 250%;
  }
  
.error-message {
    font-size: 150%;
  }
}
</style>
   