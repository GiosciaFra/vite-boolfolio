<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data (){
    return{
      
    }

  },

  components : {
    AppHeader,
    AppFooter
  },

  mounted (){
    
  },

  methods: {
    
  },

}


</script>

<template>

  <AppHeader></AppHeader>
  <router-view></router-view>
  <AppFooter></AppFooter>

</template>

<style lang="scss">


</style>
