<template>
  <div class="container">
    <header class="flex-container">
      <div class="social-block">
        <ul>
          <li><a href="#"><i class="fa fa-facebook"></i></a></li>
          <li><a href="https://vk.com/club168899861"><i class="fa fa-vk"></i></a></li>
          <li><a href="#"><i class="fa fa-instagram"></i></a></li>
          <li><a href="#"><i class="fa fa-youtube-play"></i></a></li>
        </ul>
      </div>
      <div class="links-block">
        <ul>
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">About</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/music">Music</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/tour">Tour</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/gallery">Gallery</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/epk">Epk</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact">Contact</nuxt-link>
          </li>
        </ul>
      </div>
    </header>
    <nuxt />
    <footer>
     &copy;2018 by Max Kot
    </footer>
  </div>
</template>

<style>
.footer p {
  text-align: center;
}
  a {
    color: black
  }

  .container {
    margin: 0 auto;
    max-width: 1000px;
  }

  .fa-facebook:hover {
    color: #3B5998
  }

  .fa-vk:hover {
   
    color: #4c75a3
  }

  .fa-instagram:hover {
    color: #ffc0cb
  }

  .fa-youtube-play:hover {
    color: #ff0000
  }

  .flex-container {
    display: flex;
    flex-direction: row;
  }

  

  .social-block,
  .links-block {
    display: inline-block;
  }

  .social-block>ul>li {
    display: inline-block;
    margin-right: 15px;
  }

  .links-block>ul>li {
    display: inline-block;
    margin-left: 10px
  }

  .links-block>ul>li a {
    text-decoration: none;
    text-transform: uppercase
  }

  .nuxt-link-exact-active {
    color: #27D3B4
  }

  @media only screen and (max-width: 480px) {
    .social-block{
      width:100%;
    }
    .links-block {
      width:0;
      visibility: hidden;
    }
  }

.text-wrap{
  width:0%;
}

body{
  overflow-x:hidden;
}
  .links-block {
    padding-right: 50px;
  }

</style>
<script>
export default {
  data (){
    return{
      year:2018
    }
  }
}
</script>
