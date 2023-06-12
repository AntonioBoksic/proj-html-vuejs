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
      store,
    }
  },
  methods: {
   
  },
  created(){
    
  },
}
</script>

<template>

  
  <PageHeader/>
  <PageMain/>
  <PageFooter/>

</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;

</style>

