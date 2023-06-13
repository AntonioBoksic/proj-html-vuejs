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
  <section class="jumbotron">


    <div class="container">

      <section class="content-jumbotron">
      <h1>The biggest platform for your growth.</h1>
      <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form</p>
      <button>Read More</button>
      </section>

      <img src="../public/img/27-1.png" alt="">

    </div>

  </section>
  <PageMain/>
  <PageFooter :lista1="Lista1Footer" :lista2="Lista2Footer" />

</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;

.jumbotron{

  .container{
    width: 90%;
    height: 430px;
    border: green 1px solid;
    margin: 0 auto;
    position: relative;
    background-color: #f2f7ff;

    .content-jumbotron {
      padding-left: 20px;
      padding-top: 40px;
      width: 40%;

      h1 {
        font-size: 44px;
        line-height: 66px;
      }

      p{
        color: #8e989f;
        font-size: 18px;
        line-height: 26px;
        margin-bottom: 30px;
      }

      button{
        background-color: #377dff;
        color: white;
        border: none;
        border-radius: 4px;
        padding: 10px 20px;
      }
    }

    img{
      position: absolute;
      right: 20px;
      top: 20px;
    }
  }
}

</style>

