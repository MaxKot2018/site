<template>
  <div class="flex-container">
    <div class="text-wrap">
      <div class="text-item">
        <h2>I like Anime</h2>
      </div>
      <div class="text-item">
        <h1>Anime is very interesting </h1>
      </div>
    </div>
    <div class="main-img"><img src="https://pp.userapi.com/c830609/v830609291/ff940/VEciiiNtJaE.jpg" width="800" height="500"
        alt="Happy Potato"></div>
  </div>
</template>
<style>
  .main-img {
    width: 80%;

  }

  .text-wrap {
    width: 20%;
    position: relative;
  }

  .text-wrap .text-item {
    position: absolute;
    left: 90px;
  }

  .text-wrap h1 {
    font-size: 50px;
    background: #ffffff;
    display: inline;
  }

  .text-wrap h2 {
    position: absolute;
    background: #ffffff
  }

  .text-wrap .text-item:nth-child(1) {
    top: 200px;
  }

  .text-wrap .text-item:nth-child(2) {
    top: 300px;
  }

  .text-wrap .text-item h1 {
    background: #ffffff;
    padding: 3px;
    letter-spacing: 7px;
    text-transform: uppercase;
  }

</style>
