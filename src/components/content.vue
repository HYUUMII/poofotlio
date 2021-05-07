<template>
  <div>
    <div id="content">
      <router-view class="router"></router-view>
      <div id="top" ><img id="imgtop" src="../assets/vectorbg.svg" alt=""></div>
      <div id="mid"></div>
      <div id="bot"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "./src/styles/variables.scss";

#content {

  background: rgb(255, 125, 125);
  background: linear-gradient(
    0deg,
    rgba(255, 125, 125, 1) 0%,
    rgba(255, 180, 249, 1) 50%,
    rgba(255, 125, 125, 1) 100%
  );
}
#top {
  height: 800px;
  
  #imgtop {
    
    z-index: 1;
    top: 100px;
  background-attachment: fixed;
  background-position: center;
  height: 100%;
  width: 100%;
  
  }
}
#mid {
  z-index: -1;
  height: 700px;
  background-image: url("https://i.imgur.com/Ewsbe5n.jpg");
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  opacity: 0.7;
}
#bot {
  height: 0px;
}

.router {
  position: absolute;
}
</style>

