<template>
  <div id="app">
     <CustomTitle :title="message" :subtitle="subtitle"/>
    <img alt="Vue logo" src="./assets/logo.png" />
    <!-- <HelloWorld msg="ciao a tutti" /> -->
    <Pokemons />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import CustomTitle from "./components/CustomTitle.vue";
import Pokemons from "./pages/Pokemons.vue";

export default {
    name: "App",
    components: {
        // HelloWorld
        CustomTitle,
        Pokemons
    },
    data(){
        return{
            message: "Pokemon API",
            subtitle: "Qui troverai tutti i Pokemon"

        }
    }

};
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
