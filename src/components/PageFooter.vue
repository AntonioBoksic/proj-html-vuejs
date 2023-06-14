<script>


// import { store } from "./../store.js";

export default {

  name: "PageFooter",
  props: {
    lista1: Array,
    lista2: Array
    },

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
  <footer>

    <div class="container">

        <!-- box con logo copyright -->
        
        <div class="box">
            <img src="../../public/img/35.png" alt="">
            <p>it is a long established fact that a reader wil be distracted by the readable content.</p>
            <div class="copyright">Copyright @ 2018 <span style="color: #377dff;">Sofbox</span></div>
        </div>
        

        <!-- lista1 -->
        <ul class="box">
            
            <li class="titolo-lista">
                <h2>Menù</h2>
            </li>
            <!-- popolo lista dinamicamente con dati nell array Lista1Footer passato con props lista1 -->
            <li v-for="(link,index) in lista1" :key="index">
                <a :href="link.url">
                    {{link.text}}
                </a>
                   
            </li>
        
        </ul>
        

        <!-- lista2 -->
        <ul class="box">
            <li class="titolo-lista">
                <h2>About Us</h2>
            </li>

            <!-- popolo lista dinamicamente con dati nell array Lista1Footer passato con props lista1 -->
            <li v-for="(link,index) in lista2" :key="index">
                <a :href="link.url">
                    {{link.text}}
                </a>
                   
            </li>

           
        </ul>

        <!-- lista 3 -->
        <ul class="box">
            <li class="titolo-lista">
                <h2>Quick Links</h2>
            </li>

            <!-- popolo lista dinamicamente con dati nell array Lista1Footer passato con props lista1 -->
            <li v-for="(link,index) in lista1" :key="index">
                <a :href="link.url">
                    {{link.text}}
                </a>
                   
            </li>

            
           
        </ul>
    

    </div>

  </footer>

</template>

<!-- STILE -->

<style scoped lang="scss">
footer {
    height: 200px;
    border: #eff1ef 1px solid;
    color: #8e989f;
    margin-top: 50px;

    .container {
        height: 100%;
        width: 75%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;

        .box {
            height: 100%;
            width: calc(25% - 10px);
            padding: 20px 5px 0px 5px;

            

                li{
                
                    margin: 5px 0px;
                }

                h2{
                color: black;
                margin-bottom: 10px;
                }

                img {
                height: 50px;
                width: 150px;
                }

            
            

            
        }
    }
}

a {
    color: #8e989f;
}



</style>


