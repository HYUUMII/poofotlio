
<template>
  <div>
    <div id="header">
      <div id="header1">
        <div id="Logo">
          <img src="../assets/logo.png" height="60px" width="70px" alt="" />
        </div>

        <div class="flex" id="header2">
          <div id="Home"><router-link to="/">Home</router-link></div>
          <div id="PnA">
            <router-link to="/About">Projects and Art</router-link>
          </div>
          <div id="CV"><router-link to="/CV">My CV</router-link></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import './src/styles/variables.scss';
#header {
  box-shadow: 0px 10px 60px rgb(75, 75, 75);
  padding-right: 100px;
  padding-left: 100px;
  background-color:map-get($Colorscheme, backgroundcol);
}
#header1 {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: white;
  height: 70px;
  padding: 20px;
  
}

#header2 {
  min-width: 320px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  
}

a {
  font-family: "Poppins", sans-serif;
  color: #616161;
  font-weight: lighter;
  font-size: 15px;
  text-align: center;
  text-decoration: none;

}

.flex {
  display: flex;
  justify-content: space-evenly;
  flex-flow: nowrap;
}
</style>

