<template>
  <div>

    <router-link to="/Home/Classifies" class="navbar-brand text-black">Back</router-link>
    <div class="container text-center">
      <h2> Misc &amp; Services</h2>
      <img src="../photos/vines2.png" width="600" alt="">
    </div>

    <div class="ads">
    <div class="container-fluid text-center">
      <div class="row">

        <div class="col-md-12">
          <div class="card">
            <div class="card-block p-3">
              <p class="card-text">
              <p>Looking for a Cargo Trailer?</p> Come to Young Wells Cargo in  <p>Layton Utah
              570 North Main <br>
              Mention you have a lot in Sunridge and receive a discount.
              Call Randy Taylor 801-807-8647 <br>
              <a href="mailto:randy.taylor@youngwellscargo.com">email randy.taylor@youngwellscargo.com</a>
            </p>
            </div>
          </div>
          <hr>
        </div>

        <div class="col-md-6">
          <div class="thumbnail resize">
              <img v-img:group src="../photos/class6.jpg" alt="">
            </div>
          </div>


        <div class="col-md-6">
          <div class="thumbnail resize">
              <img v-img:group src="../photos/class7.jpg" alt="">
            </div>
          </div>

        <div class="col-md-6">
          <div class="thumbnail resize">
              <img v-img:group src="../photos/class8.jpg" alt="fffff" >
            </div>
        </div>

        <div class="col-md-6">
          <div class="thumbnail resize">
            <img v-img:group src="../photos/class1.jpg" alt="">
          </div>
        </div>



        <div class="col-md-6">
          <div class="thumbnail resize">
            <img  v-img:group src="../photos/class2.jpg" alt="">
          </div>
        </div>


        <div class="col-md-6">
          <div class="thumbnail resize">
            <img v-img:group src="../photos/class3.jpg" alt="">
          </div>
        </div>


        <div class="col-md-6">
          <div class="thumbnail resize">
            <img v-img:group src="../photos/class4.jpg" alt="">
          </div>
        </div>


        <div class="col-md-6">
          <div class="thumbnail resize">
            <img v-img:group src="../photos/class5.jpg" alt="">
          </div>
        </div>

      </div>
      </div>
    </div>
  </div>
</template>


<style>
  .resize{
    width: 100px;
    margin-left: 50px;
  }
  .ads{
    margin-top: 30px;
  }
</style>
