<template>
  <div class="container">
      <div class="row justify-content-center">
          <div class="col-sm-4 mt-2 text-center">
              <h2> Двор </h2>
          </div>
      </div>
      <div class="row justify-content-center">
          <div class="col-sm-10 pt-2 text-center">
              <div class="row pt-4">
                  <p>Двор состоит из 3х террас. На одной из них расположена сушилка, на 2х других столы, стулья,
                      скамейки. Во дворе расположен мангал и тандыр. Вокруг террас зеленая зона с цветниками и
                      деревьями. 
                  </p>
              </div>
               <div class="row pt-4 justify-content-center">
                  <div class="col-sm-3 p-2 text-center">
                        <img v-img:yard src="/images/outside/yard_1.jpg" class="my_img img-fluid">
                 </div> 
                    <div class="col-sm-3 p-2 text-center">
                        <img v-img:yard src="/images/outside/yard_2.jpg" class="my_img img-fluid">
                 </div> 
                     <div class="col-sm-3 p-2 text-center">
                        <img v-img:yard src="/images/outside/yard_3.jpg" class="my_img img-fluid">
                 </div> 
                    <div class="col-sm-3 p-2 text-center">
                        <img v-img:yard src="/images/outside/yard_4.jpg" class="my_img img-fluid">
                 </div> 

              </div>
              
          </div>
      </div>
          <span class="card border-bottom-5 border-primary mt-4 mb-4"></span>
          <div class="row justify-content-center">
          <div class="col-sm-4 mt-2 text-center">
              <h2> Общая кухня </h2>
          </div>
      </div>
      <div class="row justify-content-center">
          <div class="col-sm-10 pt-2 text-center">
              <div class="row pt-4">
                  <p>Гостевой дом оборудован общей кухней, оборудованной газовой плитой, электрической духовкой,
                          микроволновкой, холодильником, электрическим чайником. Есть полный комплект посуды. 
                  </p>
              </div>
               <div class="row pt-4 justify-content-center">
                  <div class="col-sm-3 p-2 text-center">
                        <img v-img:kitchen src="/images/outside/kitchen_1.jpg" class="my_img img-fluid">
                 </div> 
                    <div class="col-sm-3 p-2 text-center">
                        <img v-img:kitchen src="/images/outside/kitchen_2.jpg" class="my_img img-fluid">
                 </div> 
                     <div class="col-sm-3 p-2 text-center">
                        <img v-img:kitchen src="/images/outside/kitchen_3.jpg" class="my_img img-fluid">
                 </div> 
                    <div class="col-sm-3 p-2 text-center">
                        <img v-img:kitchen src="/images/outside/kitchen_4.jpg" class="my_img img-fluid">
                 </div> 

              </div>
              
          </div>
      </div>
            
     
    </div>              
              
          
      
  
</template>

<script>
export default {
    layout:"default",
}

</script>
