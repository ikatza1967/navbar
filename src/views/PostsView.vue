<template>
    <div class="posts">
        <!-- row divide pantalla  -->
        <div class="row">
            <!-- divide pantalla en columnas        -->
                <div class="col-lg-6"> 
                    <div class="img cont"> 
                      <img src="@/assets/img/iosubook.svg" alt=""> 
                      <h2 class="text-center text-lg-start">
                        Vive la vida de otra manera
                      </h2>
                    </div>
                </div>
                  <div class="col-lg-6">
              <CardComp title="Titulo uno" parrafo="Hola desde postswiew"> </CardComp>
              <!-- <CardComp title="Aupa tu"> </CardComp>
              <CardComp title="Gora gu"> </CardComp>
              <CardComp title="Egunon"> </CardComp> -->
                </div> 
            </div>
    </div>
</template>
<script>
import CardComp from"../components/CardComp.vue";
export default {
    name:'PostsView',
     components:{
        CardComp
     }  
}
</script>
<style>



</style>