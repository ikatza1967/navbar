<template>
    <div class="posts">
        <div class="row mx-0">
            <!-- divide pantalla en columnas        -->
                <div class="col-lg-6"> 
                    <div class="img-cont"> 
                      <img src="@/assets/img/iosubook.svg" alt=""> 
                      <h2 class="text-center text-lg-start">
                        Vive la vida de otra manera
                      </h2>
                    </div>
                </div>
                  <div class="col-lg-6">
                    <card-comp :btns="btnArray" class="mx-auto card-comp">
                    <template #default>
                      <form>
                     <div class="mb-3 mt-2">
                      <input type="Email" 
                             class="form-control" 
                             placeholder="email"  /> 
                  </div>
                  <div class="mb-3 mt-2">
                     <input type="Pasword" 
                            class="form-control" 
                            placeholder="Contraseña"
                           />  
                      </div>
                      </form> 
                    </template>
                    <template #footer>
                      <hr />
                      <button class="btn btn-success">Crear cuenta</button>
                    </template>
                      </card-comp>    
                  </div>
                </div>
              </div> 
</template>
<script>
import CardComp from"../components/CardComp.vue";
export default {
    name:'PostsView',
     components:{    
      name:'PostsView',
          CardComp,
     },
     data(){
      return {
        btnArray: [
            {
            txt:"Iniciar Sesion",
            class:'btn-primary',
          },
          {
          txt:"Olvidaste tu contraseña",
          class: '',
         },
        
        ],
      }
     },
}

</script>
<style scoped>
  h2 {
    max-width: 470px;
    margin:auto;
    font-size:1.8rem
  }
  .posts{
  max-width: 895px;
  margin-top:auto;
  } 
  .img-cont{
    display:flex;
    flex-direction: column;

  }
  img{
    max-width: 315px;
    margin-top: 1em auto 0 auto;
  }
.card-comp{
  max-width: 398px;
  
}
.btn-success{
  margin:auto;
  min-width: 195px;
}
@media (min-width:992px){
  .posts{
    margin: 4em auto;
  }
  img{
    margin: 0;
    margin-top: 5.6em;

  }
  h2{
    margin: 0;
    margin-top: -0.8em;
    margin-left:0.8em;
  }
  .card-comp{
    margin-top: 3rem;
  }
  
} 






</style>   

