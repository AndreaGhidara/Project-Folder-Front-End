<script >
  import AppHeader from './components/AppHeader.vue';
  import AppFooter from './components/AppFooter.vue';


  export default {
    components:{
      AppHeader,
      AppFooter
    },
    data(){
        return{
            dato:42,
        }
    }
}
</script>

<template>
  <!-- HEADER -->
  <header>
    <AppHeader />
  </header>
  <!-- MAIN -->
  <main>
      <router-view>

      </router-view>
  </main>
  <!-- Footer -->
  <footer>
    <AppFooter />
  </footer>
</template>

<style scoped>

</style>
