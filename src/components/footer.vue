<template>
  <div>
    <div id="footer">
      <div id="headline">
        <h1 id="hl1">CONTACT ME</h1>
        <h1 id="hl2">CONTACT ME</h1>
      </div>

      <div id="socials">
        <v-btn
          
          fab
          dark
          x-large
          color="#FF25AF"
          onclick="location.href='https://www.facebook.com/AugustPaintings';"
          ><v-icon dark> mdi-facebook </v-icon>
        </v-btn>

        <v-btn
          
          fab
          dark
          x-large
          color="#FF25AF"
          onclick="location.href='https://www.instagram.com/hyuumii/';"
          ><v-icon dark> mdi-instagram </v-icon>
        </v-btn>

        <v-btn
          
          fab
          dark
          x-large
          color="#FF25AF"
          onclick="location.href='mailto:itslaurette@gmail.com';"
          ><v-icon dark> mdi-email </v-icon>
        </v-btn>

        <v-btn
          
          fab
          dark
          x-large
          color="#FF25AF"
          onclick="location.href='https://linkedin.com/in/lauraaugustyte/';"
          ><v-icon dark> mdi-linkedin </v-icon>
        </v-btn>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "./src/styles/variables.scss";

#footer {
  display: flex;
  flex-direction: column;
  h1 {
    font-family: "Poppins" !important;
    font-weight: medium;
  }
}

#headline {
  width: 100%;
  margin-top: -30px;
  position: relative;
  
  #hl1 {
    position: absolute;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 2;
    color: white !important;
    margin-top: -1px;
  }
  #hl2 {
    position: absolute;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    text-align: center;
    color: #ff25af !important;
    z-index: 3;
  }
  @media (min-width: 768px) {
    margin-top: -60px;
    h1 {
      font-size: 80px;
    }
    #hl1 {
      position: absolute;
      margin-left: auto;
      margin-right: auto;
      left: 0;
      right: 0;
      text-align: center;
      z-index: 2;
      color: white !important;
      margin-top: -20px !important;
    }
    #hl2 {
      position: absolute;
      margin-left: auto;
      margin-right: auto;
      left: 0;
      right: 0;
      text-align: center;
      color: #ff25af !important;
      z-index: 3;
    }
  }
}

#socials {
  margin-top: 25px;
  padding: 10% 0% 5% 0%;
}
</style>