<template>
  <div class="About">
    <div id="About">
      <div class="artdivs" id="Art1">
        <img src="../assets/assignmentLauraA4.png" alt="" />
      </div>
      <div class="artdivs" id="Art2">
        <img src="../assets/The Great Auk on Iceberg.png" alt="" />
      </div>
      <div class="artdivs" id="Art3">
        <img src="../assets/strawberry squidd.png" alt="" />
      </div>
      <div class="artdivs" id="Art4">
        <img src="../assets/Ellie_Illustration_jpg.jpg" alt="" />
      </div>
      <div class="artdivs" id="Art5">
        <img src="../assets/Thumbnail_edit.png" alt="" />
      </div>
      <div class="artdivs" id="Art6">
        <img src="../assets/OnADateJPG.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "About",
  components: {},
};
</script>

<style lang="scss" scoped>
@import "./src/styles/variables.scss";

#About {
  display: flex;
  flex-direction: row;
  flex-flow: wrap;
  align-items: center;
  justify-content: center;
  padding-top: 10%;
  .artdivs {
    padding: 5%;
    img {
      max-height: 250px;
      width: auto;
      @media (min-width: 1000px) {
        max-height: 350px;
      }
  } 
  }
}






</style>

