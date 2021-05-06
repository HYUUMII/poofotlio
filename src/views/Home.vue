<template>
  <div class="Home">
    <div id="home">
      <div>
        <div id="h1">
          <h1>
            Hi, I'm a<br />
            Multimedia <mark class="pink">Designer</mark><br />
            Hobbyist <mark class="pink">Artist</mark> and Webtoon
            <mark class="pink">Creator</mark><br />
          </h1>
          <button id="cvbutton">
            <router-link to="/CV">Check out my CV > </router-link>
          </button>
        </div>
      </div>

      <div id="Vector">
        <img
          src="../assets/myvectorart.png"
          height="450px"
          width="480px"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>

<style lang="scss" scoped>
@import "./src/styles/variables.scss";

#home {
  display: flex;
  align-items: center;
  padding-top: 100px;
  margin-left: 140px;
}

#vector {
  display: flex;
  background-position: center top;
  justify-content: space-evenly;
}

#cvbutton {
  border-radius: 10px;
  background-color: rgba(255, 255, 255, 0);
  border: 2px solid #FF25AF;
  display: flex;
  justify-content: flex-start;
  
  
}
a {
    text-decoration: none !important;
    color: map-get($Colorscheme, Tertiary);
    font-family: "Poppins";
    font-weight: medium;
    
    
  }
h1 {
  color: white;
  size: 50px;
  text-align: left;
  padding-right:170px;
}

mark.pink {
  color: #ff25af;
  background: none;
}
</style>
