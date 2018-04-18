<template>
  <div>
    <div class="container text-center">
      <h2>Maps</h2>
      <img class="hr" src="../assets/photos/vines2.png" width="600" alt="">
    </div>
  <div class="container">
    <div class="row">
      <nav class="navbar text-center">
      <div class="container-fluid">
        <ul class="nav navbar-nav">
          <li class="active"><a href="http://sunridge.info/docs/SunridgeMapMay2008.pdf" target="_blank">Printable Map</a></li>
          <li class="active"><a href="http://sunridge.info/docs/SUNRIDGE-LOTS-MAP.pdf" target="_blank">Printable LOT Map</a></li>
          <li class="active"><a href="http://sunridge.info/docs/SunridgeHuntingMapAug2015.pdf" target="_blank">Hunting Map</a></li>
        </ul>
      </div>
    </nav>

      <div class="col-xs-12 col-sm-6">
        <div class="thumbnail resize ">
          <img v-img:group="{title: 'Map'}"  src="../assets/photos/map.jpg" alt="">
          <div class="card-block p-3">
            <div class="card-text">

            </div>
      </div>
        </div>
      </div>

      <div class="col-xs-12 col-sm-6">
          <div class="thumbnail resize">
              <img v-img:group="{title: 'GPS Map'}"  src="../assets/photos/map2.jpg" alt="">
            </div>
          </div>


    </div>
  </div>
  </div>
</template>

<style>
  .resize{
    width: 100px;
    margin-left: 200px;
  }
</style>
