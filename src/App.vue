<template>
<!-- id="app" associato a questo div non serve, è già stato dichiarato in index.html-->
  <div>
    <PageTitle></PageTitle>
    <JumboTron></JumboTron>
  </div>
</template>

<script>
import PageTitle from "./components/PageTitle.vue";
import JumboTron from "./components/JumboTron.vue";

export default {
  components: {
    PageTitle,
    JumboTron,
},
  data(){
    return {
      message: 'Hello Vue!'
    }
  },  
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
