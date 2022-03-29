<template>
  <div class="container">
      <div class="row justify-content-center">
          <div class="col-sm-4 mt-2 text-center">
              <h2>Фотогаллерея </h2>
          </div>
      </div>
      <div class="row justify-content-center">
          <div class="col-sm-4 mt-2 text-center">
              <h4>Интерьер</h4>
          </div>
      </div>
      <div class="row p-2">
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/rooms/1_etag_1.jpg" class="my_img img-fluid">
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/rooms/2_etag_1.jpg" class="my_img img-fluid">
              
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/rooms/3_etag_1.jpg" class="my_img img-fluid">
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/rooms/4mestny_1.jpg" class="my_img img-fluid">
              </figure>
          </div>

      </div>
      <div class="row p-2">
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/outside/kitchen_1.jpg" class="my_img img-fluid">
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 text-center">
              <figure>
                  <img v-img:interior src="/images/outside/kitchen_2.jpg" class="my_img img-fluid">
              
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/outside/kitchen_3.jpg" class="my_img img-fluid">
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:interior src="/images/outside/kitchen_4.jpg" class="my_img img-fluid">
              </figure>
          </div>

      </div>
      <div class="row justify-content-center">
          <div class="col-sm-4 mt-2 text-center">
              <h4>Экстерьер</h4>
          </div>
      </div>
      <div class="row p-2">
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:yard src="/images/outside/yard_1.jpg" class="my_img img-fluid">
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:yard src="/images/outside/yard_2.jpg" class="my_img img-fluid">                 
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                 <img v-img:yard src="/images/outside/yard_3.jpg" class="my_img img-fluid">
              </figure>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 pt-2 text-center">
              <figure>
                  <img v-img:yard src="/images/outside/yard_4.jpg" class="my_img img-fluid">
              </figure>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}

</script>
