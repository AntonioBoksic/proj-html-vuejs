<script>

// import { store } from "./../store.js";

export default {
    name: "PageHeader",
    props: {
    links: Array
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
  
    <header>
        <div class="container">
            <div class="logo-header">
                <img src="../../public/img/logo-2.png" alt="">
            </div>

            <ul>
                <!-- popolo lista dinamicamente con dati nell array menù passato con props links -->
                <li v-for="(link,index) in links" :key="index" >
                    <a :href="link.url" :class="link.current ? 'active' : ''">
                        {{ link.text }}
                    </a>
                </li>

                <!-- da qui popolo lista staticamente -->
                <li class="list-item-icone">
                    <div>
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </div>
                    
                    <div>
                        <i class="fa-solid fa-cart-shopping"></i>
                    
                    </div>
                </li>

                <li>
                    
                        <button>Get Started</button>
                    
                    
                </li>

            </ul>

        </div>

    </header>

</template>

<!-- STILE -->

<style scoped lang="scss">

header {
    height: 80px;
    border: black 1px solid;
    

    .container{
        height: 100%;
        width: 75%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;


        .logo-header {
        height: 50px;
        width: 50px;

        img {
            width: 100%;
            height: 100%;
        }
    }

    ul {
        display: flex;
        align-items: center;
        
        li {
            padding: 0px 10px;

            .list-item-icone {
                display: flex;

                i {
                    padding: 0px 10px;
                }
            }

            

        }

        button {
            background-color: #377dff;
            color: white;
            border: none;
            border-radius: 4px;
            padding: 10px;
        }
    }
    }

    .active {
        color: #377dff;
        padding-bottom: 15px;
        border-bottom: 2px solid #377dff;
    }

    
}


</style>


