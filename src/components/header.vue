
<template>
  <div>
    <div id="header">
      <div id="header1">
        <div id="Logo">
          <img src="../assets/logo.png" height="60px" width="70px" alt="" />
        </div>

        <div class="flex" id="header2">
          <div class="w3-container">
            <div class="w3-dropdown-hover" id="hover">
              <button class="w3-button"><v-icon>mdi-arrow-down-drop-circle</v-icon></button>
              <div id="dropdownhover" class="w3-dropdown-content w3-bar-block w3-card-4">
                <div id="Home">
                  <router-link to="/">Home</router-link>
                </div>
                <div id="PnA">
                  <router-link to="/About">Projects and Art</router-link>
                </div>
                <div id="CV">
                  <router-link to="/CV">My CV</router-link>
                </div>
              </div>
            </div>
          </div>
          <div id="normalnav">
          <div id="Home">
            <router-link to="/">Home</router-link>
          </div>
          <div id="PnA">
            <router-link to="/About">Projects and Art</router-link>
          </div>
          <div id="CV">
            <router-link to="/CV">My CV</router-link>
          </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "./src/styles/variables.scss";
.w3-dropdown-hover:first-child, .w3-dropdown-click:hover {
  background-color: rgba(255, 255, 255, 0) !important;
}
#normalnav{
  display: none;
  @media (min-width: 768px) {
    display: flex;
    
  }
}
.w3-container {
  #dropdownhover {
    margin-left: -70px;
  }
  @media (min-width: 768px) {
    display: none;
    
  }
}
#header {
  padding-right: 10%;
  padding-left: 10%;
  background-color: map-get($Colorscheme, backgroundcol);
}
#header1 {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: rgb(255, 255, 255);
  height: 70px;
  padding: 2%;
}

#header2 {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

a {
  font-family: "Poppins", sans-serif;
  color: #616161 !important;
  font-weight: lighter;
  font-size: 12px;
  white-space: nowrap;
  text-decoration: none;
}
#Home, #Pna, #CV {
  margin: 0 10%;
}

.flex {
  display: flex;
  justify-content: space-evenly;
  flex-flow: nowrap;
}
</style>

