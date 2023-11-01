<template>
  <RssVue />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import RssVue from "./components/RssVue.vue";

@Options({
  components: {
    RssVue,
  },
})
export default class App extends Vue {}
</script>

<style lang="less">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0 auto;
  padding: 2% 0;
  max-width: 800px;
  background-color: gold;
}
</style>
