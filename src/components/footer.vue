<template>
  <div>
    <div id="footer">
      <div id="headline">
        <h1 id="hl1">CONTACT ME</h1>
        <h1 id="hl2">CONTACT ME</h1>
      </div>

      <div id="socials">
        <v-btn class="mx-2" fab dark x-large color="#FF25AF"
        onclick="location.href='https://www.facebook.com/AugustPaintings';"
          ><v-icon dark> mdi-facebook </v-icon>
        </v-btn>

        <v-btn class="mx-2" fab dark x-large color="#FF25AF"
        onclick="location.href='https://www.instagram.com/hyuumii/';"
          ><v-icon dark> mdi-instagram </v-icon>
        </v-btn>

        <v-btn class="mx-2" fab dark x-large color="#FF25AF"
        onclick="location.href='mailto:itslaurette@gmail.com';"
          ><v-icon dark> mdi-email </v-icon>
        </v-btn>

        <v-btn
          class="mx-2"
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
  height: 200px;
  background-color: w;
}

#headline {
  width: 100%;
  margin-top: -50px;
  position: relative;
  font-size: 44px;
  #hl1 {
    position: absolute;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 2;
    color: white !important;
    margin-top: -30px !important;
  }
  #hl2 {
    position: absolute;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    text-align: center;
    color: #FF25AF !important;
    z-index: 3;
  }
}

#socials {
  padding: 10% 0% 5% 0%;
}
</style>