<template>
    <div id="carouselExampleIndicators" class="slyderArea carousel slide carousel-fade" data-bs-ride="true">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active slide-one">
          <div class="container">
            <div class="row">
              <div class="col-md-6">
              <span>DIGITAL MEDIA AGENCY</span>
              <h1>Quality digital service <br> you really want !</h1>
              <p>we are delivering top level digital service with our
                  best experienced team, get start with us.  </p>
                  <button type="button" class="btn btn-primary" data-bs-toggle="button">Get quote</button>
              </div>
              <div class="col-md-6">  
              <div class="img-box">
               <img src="/image/A.jpg" class="d-block w-100 imgArea" alt="Slide 1">
              </div>           
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item slide-two">
          <div class="container">
            <div class="row">
              <div class="col-md-6">
              <span>DIGITAL MEDIA AGENCY</span>
              <h1>Quality digital service <br> you really want !</h1>
              <p>we are delivering top level digital service with our
                  best experienced team, get start with us.  </p>
                  <button type="button" class="btn btn-primary" data-bs-toggle="button">Get quote</button>
              </div>
              <div class="col-md-6">  
              <div class="img-box">
               <img src="/image/B.jpg" class="d-block w-100 imgArea" alt="Slide 2">
              </div>           
              </div>
            </div>
          </div>
        </div>
                <div class="carousel-item slide-three">
          <div class="container">
            <div class="row">
              <div class="col-md-6">
              <span>DIGITAL MEDIA AGENCY</span>
              <h1>Quality digital service <br> you really want !</h1>
              <p>we are delivering top level digital service with our
                  best experienced team, get start with us.  </p>
                  <button type="button" class="btn btn-primary" data-bs-toggle="button">Get quote</button>
              </div>
              <div class="col-md-6">  
              <div class="img-box">
               <img src="/image/D.jpg" class="d-block w-100 imgArea" alt="Slide 3">
              </div>           
              </div>
            </div>
          </div>
        </div>
      </div>
      <button class="pre carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class=" visually-hidden">Previous</span>
      </button>
      <button class="next carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

</template>

<script>
export default {
  name: 'slider',
}
</script>

<style>
.slyderArea{
  margin: 0;
  padding: 0;
  width: 100vw;
  height: auto;
}
.img-box{
  width: 500px;
}
.slide-one{
   background: rgb(137,255,244);
   background: linear-gradient(0deg, rgba(137,255,244,1) 0%, rgba(14,23,156,1) 100%); 
}
.slide-two{
    background: rgb(95,142,224);
    background: linear-gradient(180deg, rgba(95,142,224,1) 0%, rgba(209,226,225,1) 100%); 
}
.slide-three{
  background: rgb(64,108,107);
  background: linear-gradient(180deg, rgba(64,108,107,1) 0%, rgba(45,201,194,1) 100%);  
}
.btn {
  border-radius: 25px;
}
.carousel-item .row{
  margin: 10% 0;
}
.carousel-item span{
  margin:10px;
  font-size:20px;
  font-weight:700;
  color:red;
}
.carousel-item h1{
  margin-top:30px;
  font-weight:bold;
  color:#ffff;
}
.carousel-item p{
  margin:30px 0 50px;
  font-size:16px;
  color:#ffff;
}

</style>