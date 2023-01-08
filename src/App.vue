<template>
  <div id="app">
    <HeaderComp />
    <MainComp />
  </div>
</template>

<script>
import HeaderComp from "./components/HeaderComp.vue";
import MainComp from "./components/MainComp.vue";

export default {
  name: "App",
  components: {
    HeaderComp,
    MainComp,
  },
  methods: {
    // getInfo(){
    //   axios.get('https://api.themoviedb.org/3/movie/550?api_key=a82e1cf4903be9f664ae2bdb4205730a').then( (response) => {
    //     this.dataFilms = response.data.response
    //   } )
    // }
  },
};
</script>



<style scoped lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background: #1e2d3b;
  height: 100vh;
}
body {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>