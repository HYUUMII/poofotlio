 <template>
  <div class="Home">
    <div id="home">
      <div>
        <div id="h1">
          <h1>
            Hi, I'm a<br />
            Multimedia <span class="pink">Designer<br /></span>
            Hobbyist <span class="pink">Artist</span> and Webtoon
            <span class="pink">Creator<br /></span>
          </h1>

          <v-btn id="cv">
              <router-link to="/CV">Check out my CV > </router-link></v-btn>
          
          
      
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
  padding-top: 150px;
  margin-left: 175px;
}

#vector {
  display: flex;
  background-position: center top;
  justify-content: space-evenly;
}

#cv {
  display: flex;
  justify-content: flex-start;
  border-radius: 10px;
  margin-top: 20px;
  background-color: #FF25AF;
  border: none;
  
  
}





      





a {
    text-decoration: none !important;
    color: white !important;
    font-family: "Poppins";
    font-weight: medium;
  }

h1 {
  color: white;
  size: 50px;
  text-align: left;
  padding-right:170px;
}

.v-application .pink, .pink {
  
  color: #ff25af;
  background: none !important;
  background-color: none !important;
}


</style>