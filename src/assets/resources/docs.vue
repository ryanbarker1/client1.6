<template>
<div>
  <div class="container text-center">
    <h2>Docs &amp; Forms</h2>
    <img src="../photos/vines2.png"width="600" alt="">
  </div>

  <div class="container-fluid link text-center">
    <div class="row">
      <div class="col-xs-12 col-md-6" >
        <div class="card" style="margin-left: 50px;">
          <div class="card-block p-4">
            <ul class="map">
              <router-link to="/Home/Resources" active-class="active" tag="li"><img src="../photos/rules.png" width="350px" alt=""></router-link>
            </ul>
          </div>
        </div>
      </div>

      <div class="col-xs-12 col-md-6" >
        <div class="card" style="margin-left: 50px;">
          <div class="card-block p-4">
            <ul class="map">
              <router-link to="/Map" active-class="active" tag="li"><img src="../photos/map.png" width="180px" alt=""></router-link>
            </ul>

          </div>
        </div>
      </div>

    </div>
  </div>

</div>
</template>


<style>
  .map{
  list-style: none;
    margin-left: 100px;
  }

  @media screen and (max-width: 400px) {
    .map{
      margin: 0;
    }
  }
</style>
