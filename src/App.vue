<script>
import PageHeader from './components/PageHeader.vue';
import PageMain from './components/PageMain.vue';
import PageFooter from './components/PageFooter.vue';
// import { store } from "./store";




export default {
  components: {
    PageHeader,
    PageMain,
    PageFooter,
  },
  data() {
    return {
      // store,
      menuHeader: [ 
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
      Lista1Footer: [ 
        {
          text:"About us",
          url:"#",
          
      },
      {
          text:"Theme",
          url:"#",
          
      },
      {
          text:"Features",
          url:"#",
          
      },
      {
          text:"Pricing",
          url:"#",
          
      },
      {
          text:"Blog",
          url:"#",
          
      },
      ],
      Lista2Footer: [ 
        {
          text:"About Sofbox",
          url:"#",
          
      },
      {
          text:"Roadmap",
          url:"#",
          
      },
      {
          text:"How it works",
          url:"#",
          
      },
      {
          text:"Team",
          url:"#",
          
      },
      {
          text:"News",
          url:"#",
          
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

  
  <PageHeader :links="menuHeader"/>
  <PageMain/>
  <PageFooter :lista1="Lista1Footer" :lista2="Lista2Footer" />

</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;

</style>

