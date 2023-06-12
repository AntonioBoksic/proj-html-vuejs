<script>
import PageHeader from './components/PageHeader.vue';
import PageMain from './components/PageMain.vue';
import PageFooter from './components/PageFooter.vue';
import { store } from "./store";




export default {
  components: {
    PageHeader,
    PageMain,
    PageFooter,
  },
  data() {
    return {
      // store,
      menu: [ 
        {
          text:"Home",
          url:"#",
          current: true
      },
      {
          text:"About Us",
          url:"#",
          current: false
      },
      {
          text:"Feature",
          url:"#",
          current: false
      },
      {
          text:"Testimonials",
          url:"#",
          current: false
      },
      {
          text:"Contact Us",
          url:"#",
          current: false
      },
      ],
    }
  },
  methods: {
   
  },
  created(){
    
  },
}
</script>

<template>

  
  <PageHeader :links="menu"/>
  <PageMain/>
  <PageFooter/>

</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;

</style>

