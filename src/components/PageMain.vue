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

<!-- sezione contact -->
<section class="contact">

  <div class="container">
    <h2>Contact with our team</h2>
    <p class="pcenter">If you are planning on developing a product landing.</p>

    <div
    class="container-flex">
      <!-- mappa -->
      <div class="map-img">
        <img src="../../public/img/StaticMapService.GetMapIma.png" alt="">

        <div class="address">
          
          <div>
            <div> <strong>Storey Ave</strong></div>
            <div class="city">San Francisco, California 94129</div>
            <div class="visualizza-mappa">visualizza mappa più grande</div>

          </div>
          
          
          <div class="indicazioni">
            <!-- <div>qui ci va immagine</div> -->
            
            <div>indicazi...</div>
          </div>
        
        </div>

        <div class="zoom-map">
          <div class="zoom-in">
            <i class="fa-solid fa-plus"></i>
          </div>

          <div class="zoom-out">
            <i class="fa-solid fa-minus"></i>
          </div>

        </div>

      </div>
      <!-- form -->
      <div class="form">

        <!-- logo -->
        <div class="logo">
          <img src="../../public/img/35.png" alt="">
        </div>
        <!-- indirizzo -->
        <div>
        <strong>9840 Shore St. Fond Du Lac, WI 54935</strong>
        </div>

        <div class="contatti">
          <p>0 1223 456 789</p>
        <p>mail@sofbox.com</p>

        </div>
        

        <!-- icone -->
        <div class="icone">
          <div class="icona">
            <i class="fa-brands fa-facebook-f"></i>
          </div>
          <div class="icona">
            <i class="fa-brands fa-twitter"></i>
          </div>
          <div class="icona">
            <i class="fa-brands fa-reddit"></i>
          </div>
          <div class="icona">
            <i class="fa-brands fa-instagram"></i>
          </div>

        </div>

        <!-- get in touch -->
        <div class="getintouch">Get in Touch</div>

        <!-- sezione inpiut -->
        <section class="input-section">

          <div class="nomeMail">
            <input classe="nome_input" type="text" placeholder="Your Name">
            <input type="text" placeholder="Your Email">
          </div>

          <div>
            <input type="text" placeholder="Your Subject">
          </div>

          <div>
            <input class="yourMessage" type="text" placeholder="Your Message">
          </div>

        </section>
        
        <!-- bottone finale -->
        <button>Send Message</button>

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

// sezione contact 
.contact{
  padding-top:$paddingtop-sections ;

  .container {
    height: 100%;
    width: 75%;
    margin: 0 auto;

    h2{
      text-align: center;
    }

    p{
      text-align: center;
    }

    .container-flex{
      padding-top: 30px;
      display: flex;

      .map-img {
        position: relative;

        

        .address{
          padding: 10px;
          position: absolute;
          top: 5px;
          left: 5px;
          background-color: white;
          display: flex;
          .city{
          color: grey;
          font-size: 14px;
        }

        .visualizza-mappa {
          padding-top: 20px;
          color: $primary;
        }

        .indicazioni {
          color: $primary;
          padding-left: 30px;
          
        }

        }

        .zoom-map{
          position: absolute;
          top: 360px;
          right: 5px;
          background-color: white;
          padding: 5px;
          font-size: 30px;
          color: grey;

          i{
            &:hover {
              cursor: pointer;
              background-color: black;
            

            }
          }

          .zoom-in {

            border-bottom: solid 1px #eff1ef;

          }

          .zoom-out{
            position: relative;
            top: 3px;
          }
        }
        
      }

      .form {
        padding-left: 20px;

        
        

        .logo{
          padding-bottom: 20px;
        }

        .contatti{
          padding: 10px 0px;

          p{
          text-align: start;
          
        }
        }

        .icone{
          display: flex;
          color: $primary;
          margin: 20px 0px;

          .icona{
            
            
            border: 1px solid #eff1ef;
            height: 30px;
            width: 30px;
            text-align: center;
            line-height: 30px;
            vertical-align: middle;
            margin-right: 5px;

            

            // margin: 0px 5px;
            // padding: 2px;
            
          }
        }

        .getintouch {
          font-size: $cardtitlefontsize;
          padding: 30px 0px;
        }

        .input-section{

          input {
            margin: 20px 0px;
            width: 100%;
            height: 40px;
            border:1px solid #eff1ef;
            padding-left: 20px;
            padding-top: none;

          }

          .nomeMail{
            width: 100%;
            display: flex;
            justify-content: space-between;

            

            input{
              width: calc(50% - 10px);
              
              
            }

          }

          .yourMessage{
            height: 150px;
            text-align: start;
            line-height: 150px;
            vertical-align: top;
            text-align:start
            
            
            
            

          }

          
        

          
        }

        

        .button{
          margin-top: 20px;
        }
      }
    }

  }

}

</style>


