<template>
  <div id="app">
    <div class="menu">
      <div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="item active">
          <img src="./assets/g13138.png" alt="First slide">
          <div class="container">
            <div class="carousel-caption">
              <h1>Małe Średniowiecze</h1>
              <p>Produkcja dzieciencych kostiumów</p>
            </div>
          </div>
        </div>
        <div class="item">
          <img src="./assets/i13149.png" alt="Second slide" >
          <div class="container">
            <div class="carousel-caption">
              <h1>Małe Średniowiecze</h1>
              <p>Produkcja dzieciencych kostiumów</p>
            </div>
          </div>
        </div>
        <div class="item">
          <img src="./assets/g13162.png" alt="Third slide" >
          <div class="container">
            <div class="carousel-caption">
              <h1>Małe Średniowiecze</h1>
              <p>Produkcja dzieciencych kostiumów</p>
            </div>
          </div>
        </div>

        <div class="item">
          <img src="./assets/g13174.png" alt="Fourth slide" >
          <div class="container">
            <div class="carousel-caption">
              <h1>Małe Średniowiecze</h1>
              <p>Produkcja dzieciencych kostiumów</p>
            </div>
          </div>
        </div>

      </div>
        </div>
        <img src="./assets/castel.png" alt="castle_bar" style="position: absolute; left: 5%; bottom: -30%; width: 87%"/>
        <a href="https://www.facebook.com/"><img src="./assets/facebook.png" alt="nav_bar" style="position: absolute; right: 4%; bottom: -12%; width: 4%;"/></a>
        <img src="./assets/spear.png" alt="nav_bar" style="position: absolute; left: 0; bottom: -35%; width: 97%;"/>
        <router-link :to="{ name: 'Hello' }"><img src="./assets/menu.png" alt="nav_bar" style="position: absolute; right: 36%; top: 128%; width: 8%;"></router-link>
        <router-link to="/products"><img src="./assets/path3860.png" alt="nav_bar" style="position: absolute; right: 27%; top: 128%; width: 8%;"></router-link>
        <router-link to="/contact"><img src="./assets/path3864.png" alt="nav_bar" style="position: absolute; right: 18%; top: 128%; width: 8%;"></router-link>
        <router-link to="/about"><img src="./assets/path9864.png" alt="nav_bar" style="position: absolute; right: 9%; top: 128%; width: 8%;"></router-link>
        <router-link :to="{ name: 'Hello' }"><img src="./assets/g5628.png" alt="nav_bar" style="position: absolute; left: 20%; bottom: -70%; width: 30%;"/></router-link>
      </div>
      <router-view></router-view>
    </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style>
  body{
    background-color: #2b2b2a;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #ffffff;
    /*margin-top: 60px;*/
  }
  .menu{
    position: relative;
    left: 0;
    top: 0;
  }
  .carousel{
    width: 80%;
    margin-bottom: 17%;
    margin-left: 10%;
  }
</style>
