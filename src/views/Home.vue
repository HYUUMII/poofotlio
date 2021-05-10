 <template>
  <div class="Home">
    <div id="home">
      <div id="Vector">
        <img src="../assets/myvectorart.png" />
      </div>
      <div id="textbtn">
        <div id="h1"><h1>
          Hi, I'm a<br />
          Multimedia <span class="pink">Designer<br /></span> Hobbyist
          <span class="pink">Artist</span> and Webtoon
          <span class="pink">Creator<br /></span>
        </h1>
        </div>

        <v-btn id="cv">
          <router-link to="/CV">Check out my CV > </router-link>
          </v-btn>
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
  margin: 0 auto;
  @media (min-width: 1024px) {
    display: flex;
    flex-direction: row-reverse;
    justify-content: center;
    align-items: center;
  }
}

#Vector {
  padding: 20px;
  img {
    width: 100%;
    max-width: 400px;
    @media (min-width: 1024px) {
    max-width: 800px;
    padding: 50px;
  }
  }
}

#cv {
    margin: 20px;

  
  border-radius: 10px;
  margin-top: 20px;
  background-color: #ff25af;
  border: none;
}

a {
  text-decoration: none !important;
  color: white !important;
  font-family: "Poppins";
  font-weight: medium;
}
#textbtn {
  margin: 0 auto;
  padding: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  .v-btn {
    justify-content: flex-start;
    width: 200px;
  }
}
#h1 {
  padding: 20px;
  margin: 0 auto;
  color: white;
  size: 50px;
  h1 {
  text-align: left;
  font-family: "Poppins";
  font-weight: medium;
  }
  
}

.v-application .pink,
.pink {
  color: #ff25af;
  background: none !important;
  background-color: none !important;
}
</style>