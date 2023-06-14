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
<!-- sezione popular features -->
<section class="popular-features">

  <div class="circle-img">
    <img src="../../public/img/14.png" alt="">
  </div>

  <div class="container">
    <div>
      <h2>Popular features that your business needs.</h2>
      <p>faff about only a quid blower I don't want no agro bleeding chimney pot burke tosser cras nice one boot fanny.!</p>
    </div>
    <button>Explore More Features</button>
  </div>

  <div class="container">
    <!-- card 1 -->
    <div class="card-features">
      <div class="title">
        Customized Invoices
        <div class="card-features-img blue">
          <!-- mancano le immagini per queste card -->
          immagine blu

        </div>

      </div> 
    </div>
    <!-- card 2 -->
    <div class="card-features">
      <div class="title">
        Stock Management
        <div class="card-features-img red">
          <!-- mancano le immagini per queste card -->
          immagine rossa

        </div>

      </div> 
    </div>

    <!-- card 3 -->
    <div class="card-features">
      <div class="title">
        Receivable & Payables
        <div class="card-features-img green">
          <!-- mancano le immagini per queste card -->
          immagine verde

        </div>

      </div> 
    </div>

    <!-- card 4 -->
    <div class="card-features">
      <div class="title">
        Manage Buying
        <div class="card-features-img blue">
          <!-- mancano le immagini per queste card -->
          immagine blu

        </div>

      </div> 
    </div>
    
    <!-- card 5 -->
    <div class="card-features">
      <div class="title">
        Powerful & Secure
      </div> 
      <div class="card-features-img red">
        <!-- mancano le immagini per queste card -->
        immagine rossa

      </div>

      
    </div>

    <!-- card 6 -->
    <div class="card-features">
      <div class="title">
        Fastest Return Filing
      </div>
      <div class="card-features-img green">
        <!-- mancano le immagini per queste card -->
        immagine verde

      </div>

       
    </div>

    <!-- card 7 -->
    <div class="card-features">
      
        <div class="title">
          Monthly Details
        </div>
        
        <div class="card-features-img blue">
          <!-- mancano le immagini per queste card -->
          immagine blu

        </div>

      
    </div>

    <!-- card 8 -->
    <div class="card-features">
      <div class="title">
        Product Management
      </div>
      <div class="card-features-img red">
        <!-- mancano le immagini per queste card -->
        immagine rossa

      </div>

       
    </div>
    
  </div>

</section>

<!-- sezione our testimonials -->
<section class="our-testimonials">

  <!-- <div class="wave-img">
    <img src="../../public/img/15.png" alt="">
  </div> -->

  <div class="container">
    <h2>Our Testimonials</h2>
    <p class="pcenter">If you are planning on developing a product landing app or website, take a look at this beautiful crafted</p>

    <div class="cards-container">
      <!-- card1 -->
      <div class="card">

        <div class="card-img">
          <img src="../../public/img/26.jpeg" alt="">
        </div>

        <div class="title">
          Julia Aann <span> - COO Sofbox</span>
        </div>

        <p>
          At vero eos et accusuamus et iusto odio dignissimos ducimus qui blanditiis presentium vero eos et consectetur accus adip adip.
        </p>

        

      </div>

      <!-- card2 -->
      <div class="card">

        <div class="card-img">
          <img src="../../public/img/27.jpeg" alt="">
        </div>

        <div class="title">
          Mac Znder <span> - Manager Sofbox</span>
        </div>

        <p>
          At vero eos et accusuamus et iusto odio dignissimos ducimus qui blanditiis presentium vero eos et consectetur accus adip adip.
        </p>

      </div>

      

    </div>
  </div>
  

</section>

<!-- sezione latest posts -->
<section class="latest-posts">
  <div class="container">
    <h2>Latest Posts</h2>
    <p class="pcenter">If you are planning on developing a product landing.</p>

    <div class="cards-container">

      <!-- card 1 -->
      <div class="card">

        <div class="card-img">
          <img src="../../public/img/19.jpg" alt="">
          <div class="data-post">November 28, 2019</div>
        </div>

        <div class="card-content">
          <div class="title">Life Lack Meaning</div>
          <p>It is a long established fact that a reader will be distracted by the readable.</p>
        </div>
      </div>

      <!-- card 2 -->
      <div class="card">

        <div class="card-img">
          <img src="../../public/img/18.jpg" alt="">
          <div class="data-post">November 28, 2019</div>
        </div>

        <div class="card-content">
          <div class="title">Life Lack Meaning</div>
          <p>It is a long established fact that a reader will be distracted by the readable.</p>
        </div>
      </div>

      <!-- card 3 -->
      <div class="card">

        <div class="card-img">
          <img src="../../public/img/17.jpg" alt="">
          <div class="data-post">November 28, 2019</div>
        </div>

        <div class="card-content">
          <div class="title">Life Lack Meaning</div>
          <p>It is a long established fact that a reader will be distracted by the readable.</p>
        </div>
      </div>

      


    </div>

  </div>
</section>
  
</template>

<!-- STILE -->
<style scoped lang="scss">

@use '../styles/partials/variables.scss' as *;
@use '../styles/general.scss' as *;


h2 {
  font-size: 33px;
  line-height: 44px;
}

p{
  color: #8e989f;
  font-size: 18px;
  line-height: 26px;
}

// sezione popular features
.popular-features {
  position: relative;
  padding-top: $paddingtop-sections;

  .container {
    align-items: center;
    flex-wrap: wrap;

    p{
      width: 60%;
    }

    .card-features {
      width: calc(25% - 40px);
      border:black 1px solid;
      margin: 20px 0px;
      padding: 10px;


      .title {
        font-size: $cardtitlefontsize;
        
      }

      .card-features-img {
        padding-top: 10px;
        padding-bottom: 40px;
      }
      .card-features-img.blue{
        color: $primary;
      }

      .card-features-img.red{
        color: red;
      }

      .card-features-img.green{
        color: lightgreen;
      }
    }
  }
  .circle-img{
    img{ 
      position: absolute;
      transform: translate(-50%,0);
      top:0px;
      width: 350px;

    }

  }
  
}

// sezione our testimonials
.our-testimonials{
  padding-top: $paddingtop-sections;
  position: relative;

  .container{
    height: 100%;
    width: 75%;
    margin: 0 auto;
    
    
    h2 {
    text-align: center;
    z-index: 10;
    }

  .pcenter {
    text-align: center;
    padding-bottom: 50px;
    width: 46%;
    margin: 0 auto;
    z-index: 10;
    }

    .cards-container{
      
      display: flex;
      align-items: center;
      justify-content: space-between;

      .card {
        width: calc(50% - 40px);
        height: 300px;
        // border: black 1px solid;
        padding: 30px;
        box-shadow: 5px 5px 15px 2px #00000026;

        .title{
          font-size:$cardtitlefontsize ;
          text-align: center;
          padding: 30px 0px;
          

          span{
            color: #8e989f;
            font-size: 18px;
          }
        }

        .card-img {
          
          border: white 1px solid;
          width: 75px;
          height: 75px;
          margin: 0 auto;
          border-radius: 40px;

          img{
            width: 100%;
            border-radius: 40px;
          }
        }
      }

    }

  }

  .wave-img{

    img{ 
      // position: absolute;
      // transform: translate(-50%,0);
      // top:0px;
      // width: 350px;
      color: black;
      position: absolute;
      top: 0;
      transform: translate(-20%,0);
      z-index: 1;
      
      background: linear-gradient(to bottom,#f0f7ff 75%,white);
      


    }

  }

}

// sezione latest posts
.latest-posts {
  padding-top: $paddingtop-sections;
  .container{

    height: 100%;
    width: 75%;
    margin: 0 auto;
    
    h2 {
    text-align: center;
    }

  .pcenter {
    text-align: center;
    padding-bottom: 50px;
    }

    .cards-container{
      
      display: flex;
      align-items: center;
      justify-content: space-between;

      .card {
        width: calc(100% / 3 - 40px);
        height: 350px;
        border: #eff1ef 1px solid;
        padding: 10px;

        .card-content{
          padding: 15px;

          .title{
          font-size:$cardtitlefontsize ;
        }
        
        }
        
        .card-img{
          position: relative;

          .data-post{
            position: absolute;
            top: 10px;
            left: 5px;
            padding: 5px;
            border-radius: 4px;
            background-color: white;
            color: #8e989f;
          }

          img{
            width: 100%;
          
          }
        }
      }
    }
  }
}

</style>


