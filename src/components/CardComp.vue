<template>
   <div class="card">
                    <div class="card-body">
                     <h5 class="card-title">{{ title }}</h5>
                    <p class="card-text">
                        {{ parrafo }}
                    </p>
                    <a href="#" class="btn btn-primary">Ir a algún lugar</a>
                    </div>
                </div>
</template>

<script>
     export default {
           name: 'CardComp',
           props:["title","parrafo"],
           
}
</script>

<style>

</style>