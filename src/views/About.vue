<template>
  <div class="About">
    <div id="About">
    
     <div id="Art1">
        <img
          src="../assets/assignmentLauraA4.png"
          height="300px"
          width="300px"
          alt=""
        />
      </div>

      <div id="Art2">
        <img
          src="../assets/The Great Auk on Iceberg.png"
          height="300px"
          width="250px"
          alt=""
        />
      </div>

      <div id="Art3">
        <img
          src="../assets/strawberry squidd.png"
          height="300px"
          width="250px"
          alt=""
        />
      </div> 

      </div>
      <div id="About2">   

      <div id="Art4">
        <img
          src="../assets/Ellie_Illustration_jpg.jpg"
          height="250px"
          width="250px"
          alt=""
        />
      </div> 

    

      <div id="Art5">
        <img
          src="../assets/Thumbnail_edit.png"
          height="250ppx"
          width="250px"
          alt=""
        />
      </div>

      <div id="Art6">
        <img
          src="../assets/OnADateJPG.jpg"
          height="250ppx"
          width="250px"
          alt=""
        />
      </div>

      </div>


    
  
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'About',
  components: {
    
  }
}
</script>

<style lang="scss" scoped>
@import './src/styles/variables.scss';


#About {
display:flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
padding-left: 300px;
 padding-top:100px;

}

#About2 {
  padding-left: 300px;
  padding-top:50px;
display:flex;
flex-direction: row-reverse;
align-items: center;
justify-content: space-between;

}



h1 {
  padding-top:100px;
  padding-left:150x;
  margin-top: 150px;
  margin-bottom: 150x;
  margin-left: 200px;
  color: rgb(255, 255, 255);
  font-size: 100px;
  text-align: right;
  }
  

  #Art1 {
  display: flex;
  background-position: center top;
  justify-content: space-evenly;
}

</style>

