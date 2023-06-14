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
  <!-- jumbotron -->
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
  <!-- online marketing -->
  <section class="online-marketing">
    <div class="container">
      <div class="card">
        <div class="card-logo">
          <img src="../public/img/24.png" alt="">
        </div>
        <div class="card-content">
          <h3>Online Marketing</h3>
          <p>it is a long established fact that a reader will be distracted</p>
          <ul>
            <li>
              <i class="fa-solid fa-check"></i>
              SEO
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              SEM
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              Website Strategy
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              Social Management
            </li>
          </ul>
        </div>
      </div>

      <div class="card">
        <div class="card-logo">
          <img src="../public/img/24.png" alt="">
        </div>
        <div class="card-content">
          <h3>Online Marketing</h3>
          <p>it is a long established fact that a reader will be distracted</p>
          <ul>
            <li>
              <i class="fa-solid fa-check"></i>
              SEO
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              SEM
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              Website Strategy
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              Social Management
            </li>
          </ul>
        </div>
      </div>

      <div class="card">
        <div class="card-logo">
          <img src="../public/img/24.png" alt="">
        </div>
        <div class="card-content">
          <h3>Online Marketing</h3>
          <p>it is a long established fact that a reader will be distracted</p>
          <ul>
            <li>
              <i class="fa-solid fa-check"></i>
              SEO
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              SEM
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              Website Strategy
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              Social Management
            </li>
          </ul>
        </div>
      </div>
      
    </div>
  </section>

  <!-- tips & tricks -->
  <section class="tips_tricks">
    <div class="container">
      <!-- contenuto tips & tricks -->
      <div class="content-tips">
        <h2>Get tips tricks on how to skyrocket your sales.</h2>
        <p>faff about only a quid blower I don't want no agro bleeding chimney pot burke tosser cras nice one boot fanny.!</p>
        <!-- card 1-->
        <div class="card-tips analysis">
          <div class="card-tips-img">
            <img src="../public/img/510.png" alt="">

          </div>

          <div class="card-tips-content">
            <div class="title">Reporting Analysis</div>
            <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>

          </div>

        </div>
        <!-- card 2-->
        <div class="card-tips seo">
          <div class="card-tips-img">
            <img src="../public/img/511.png" alt="">

          </div>

          <div class="card-tips-content">
            <div class="title">Technical SEO Audit</div>
            <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>

          </div>

        </div>
        
      </div>
      <!-- immagine tips & tricks -->
      <div class="img-tips">
        <img src="../public/img/509.jpeg" alt="">
      </div>

    </div>
  </section>

  <PageMain/>
  <PageFooter :lista1="Lista1Footer" :lista2="Lista2Footer" />

</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;


// jumbotron
.jumbotron{

  .container{
    width: 90%;
    height: 430px;
    // border: green 1px solid;
    margin: 0 auto;
    position: relative;
    background-color: #f2f7ff;
    margin-bottom: 50px;
    border-radius: 8px;

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

      
    }

    img{
      position: absolute;
      right: 20px;
      top: 20px;
    }
  }
}

// sezione online marketing
.online-marketing {
  padding-top: $paddingtop-sections;

  .container {
    height: 100%;
    width: 75%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .card{
      // border: 1px solid black;
      width: calc(100% /3 - 20px);
      height: 250px;
      display: flex;
      

      .card-logo {
        width:20%;

        img{
          height: 55px;
          width: 55px;
        }
      }

      .card-content {
        width: 80%;

        h3{
          padding-bottom: 20px;
        }

        p{
        color: #8e989f;
        font-size: 18px;
        line-height: 26px;
        margin-bottom: 30px;
        }

        li{
          margin: 10px 0px;

          i {
            color: #377dff;
          }
        }
      }

    }
  }
}

// sezione tips & tricks
.tips_tricks{
  padding-top: $paddingtop-sections;
  .container {
    height: 100%;
    width: 75%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .content-tips {
      width: 50%;
      padding-right: 10px;

      h2 {
        font-size: 33px;
        line-height: 44px;
      }

      p{
        color: #8e989f;
        font-size: 18px;
        line-height: 26px;
      }

      .card-tips {
        // border: 1px black solid;
        display: flex;
        margin: 10px 0px;

        
        

        .card-tips-img{
          width: calc(100% / 6);
          height: 100%;
          align-self: center;

        }

        .card-tips-content{

          width: calc(100% / 6 * 5);
          padding: 15px 10px;

          .title {
            color: #377dff;
            font-size: $cardtitlefontsize;
          }

          p{
          color: #8e989f;
          font-size: 18px;
          line-height: 26px;
          
          }

        }
      }
    }

    .card-tips.analysis {
          box-shadow: 5px 5px 15px 2px #00000026;
          
        }

    .img-tips {
      width: 50%;
      padding-left: 10px;

      img{
        width: 100%;
        height: 100%
      };
    }

  }
}

// sezione popular features
.popular-features{
  .container {
    height: 100%;
    width: 75%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
}

</style>

