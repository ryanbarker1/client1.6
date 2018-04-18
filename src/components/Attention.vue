<template>
  <div>
  <div class="container text-center">
    <h2 id="top">Sunridge News</h2>
    <img src="../assets/photos/vines2.png" width="600" alt="">
  </div>
    <nav class="navbar">
      <div class="container-fluid">
        <ul class="nav navbar-nav">
          <router-link  to="/Home/News/2018" active-class="active" tag="li"><a style="color: black">2018 Season</a></router-link>
          <router-link  to="/Home/News/2017" active-class="active" tag="li"><a style="color: black">2017 Season</a></router-link>
          <router-link  to="/Home/News/2016" active-class="active" tag="li"><a style="color: black">2016 Season</a></router-link>
        </ul>
      </div>
    </nav>
  </div>

</template>

<style>
  .scroll {
    width: 100%;
    height: 350px;
    overflow: scroll;
  }

  li{
    list-style-type: none;
  }



</style>
