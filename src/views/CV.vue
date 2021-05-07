<template>
  <div class="CV">
    <div id="CV">



      <div class="resp-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/u1aLDw-QM64" 
    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
     
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



#About {
  display: flex;
  justify-content: center;
}

h1 {
  color: rgb(255, 255, 255);
  font-size: 100px;
  text-align: right;
}

.v-application .pink,
.pink {
  color: #ff25af;
  background: none !important;
  background-color: none !important;
}


.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

#CV {
  padding-bottom:100px  !important;
  padding-left: 200px;
  margin-left:250px;
  margin-bottom: 100px;
 display: flex;
 justify-content: center;
  }

  

</style>