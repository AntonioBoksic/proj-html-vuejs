<script>


// import { store } from "./../store.js";

export default {

  name: "PageMain",

  components: {
    
  },

  data() {
     return {
    //    store,
            
     }
  },

  mounted() {
    console.log("caricato");
  }
  
}
</script>

<!-- HTML -->
<template>
<!-- popular features -->
<section class="popular-features">
    <div class="container">
      <div>
        <h2>Popular features that your business needs.</h2>
        <p>faff about only a quid blower I don't want no agro bleeding chimney pot burke tosser cras nice one boot fanny.!</p>
      </div>
    <button>Explore More Features</button>
    </div>

  </section>
  
  

</template>

<!-- STILE -->

<style scoped lang="scss">

@use '../styles/partials/variables.scss' as *;
@use '../styles/general.scss' as *;

.popular-features {
  button{
  background-color: $primary;
  color: white;
  border: none;
  border-radius: 4px;
  padding: 10px 20px;
  }
}

</style>


