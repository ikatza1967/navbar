<template>
  <nav class="navbar navbar-expand-lg ">
    <div class="container justify-content-evenly" id="navbarNavAltMarkup">
      <!-- <router-link to="/" class="navbar-brand"><img src="../assets/images.jpeg" alt="foto"></router-link> -->
      <router-link to="/" class="nav-link active" aria-current="page">
        <span class="material-icons-round">
          home
        </span>
      </router-link>
         
      <router-link to="/about" class="nav-link">
            <span class="material-icons-round ">
              info
            </span>
      </router-link>
          
      <router-link to="/posts" class="nav-link">
            <span class="material-icons-round ">
             star_rate_half
            </span>
      </router-link>
    </div>
  </nav>
</template>
<script>
 export default{
name:"NavComp"
}
</script>
<style scoped>
.navbar{
  background-color: gray;
padding-bottom: 0;
padding-top: 0%;

}
 
.material-icons-round{
  font-size: 1.4rem;
  background-color:rgba(0, 38, 255, 0.329);
  padding: 0.3rem;
  border-radius: 50%;
  margin: 0.1rem;
color: antiquewhite;
}

.nav-link{
  padding: 0.2rem 1rem;
}

</style>













