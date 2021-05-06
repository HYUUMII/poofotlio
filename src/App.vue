<template>
  <div id="app">
    <myHeader id="myHeader"></myHeader>
    <myContent id="myContent"></myContent>
    <myFooter id="myFooter"></myFooter>
  </div>
</template>

<script>
import Header from "./components/header";
import Content from "./components/content";
import Footer from "./components/footer";
export default {
  components: {
    myHeader: Header,
    myContent: Content,
    myFooter: Footer
  }
}
</script>

<style lang="scss">
@import './src/styles/variables.scss';
#app {
  font-family: Poppins, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: map-get($Colorscheme, Primary);
}

#nav {
  padding: 10px;

  a {
    font-weight: bold;
    color: white;

    &.router-link-exact-active {
      color: map-get($Colorscheme, Secondary);
    }
  }

 

}
</style>
