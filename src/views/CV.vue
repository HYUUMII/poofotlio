<template>
  <div class="CV"><img id="imgtop" src="../assets/vectorbg.svg" alt="" />
    <div class="centering" id="cvcontent">
      <div class="container"> 
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/u1aLDw-QM64"></iframe>
</div>
      <div><div id="MyButton">
      <v-btn
        elevation="2"
        rounded
        dark
          x-large
          color="#FF25AF"
          onclick="location.href='https://i.imgur.com/0iq3pwc.png';"
        >MY CV IN TEXT</v-btn>
        </div></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "CV",
  components: {},
};
</script>

<style lang="scss" scoped>
@import "./src/styles/variables.scss";

.CV {
  padding: 50px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  @media (min-width: 768px) {
 display: flex;
 flex-direction: row;
 justify-content: center;
 align-items: center;
  }
}
#imgtop {
  position: absolute;
    z-index: 0;
    top: 100px;
    background-position: center;
    background-repeat: no-repeat;
    height: auto;
    width: auto;
  }
.CV.router {
  position: static  !important;
}

#cvcontent {
  flex-direction: column;
  max-width: 800px;
  @media (min-width: 1000px) {
    flex-direction: row;
  }
}

#MyButton {
 margin: 20px;
display:flex;
  align-items: center;
  justify-content:center;
  @media (min-width: 1000px) {
    margin-top: 50%;
  }
}

  
.container {
  position: relative;
  width: 100%;
  overflow: hidden;
  padding-top: 56.25%; /* 16:9 Aspect Ratio */
}

.responsive-iframe {
 
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
  border: none;
}
  

</style>