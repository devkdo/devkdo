 <template>
  <div class="home">
    <div class="menu">
      <div class="menu-item">
        Resume
      </div>
      <div class="menu-item">
        Projects
      </div>
      <div class="menu-item menu-center">
        Dev Kdo
      </div>
      <div class="menu-item">
        Travel
      </div>
      <div class="menu-item">
        About
      </div>
    </div>
    <div class="letters">
      <div class="unit unit-front">
        <img src="../assets/img/K-bg.png"/>
      </div>
      <div class="unit unit-front">
        <img src="../assets/img/A-bg.png"/>
      </div>
      <div class="unit unit-front">
        <img src="../assets/img/I-bg.png"/>
      </div>
      <div class="unit unit-bg">
        <img src="../assets/img/D-bg.png"/>
        <!-- <img src="../assets/img/D-bold.png"/> -->
      </div>
      <div class="unit unit-bg">
        <img src="../assets/img/O-bg.png"/>
        <!-- <img src="../assets/img/O-bold.png"/> -->
      </div>
      <!-- <div class="unit">
        <img src="../assets/img/K.png"/>
      </div> -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>
<style>
.home{
  width: 100%;
  margin: 5;
}
.menu{
  display: flex;
  color: white;
  align-items: center;
  justify-content: space-around;
  margin-top: 2%;
}
.menu-item{
  flex: 1;
  text-align: center;
  color: lightgray;
  font-size: medium;
}
.menu-item:hover{
  border-bottom: 2px;
}
.menu-center{
  font-size: x-large;
  color: white;
}
.letters{
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: calc(100vh - 60px);
}
.unit{
  margin: .8%;
  filter:blur(1px) opacity(.9) grayscale(1);
}
.unit:hover{
  filter:blur(0px) opacity(1) grayscale(0) drop-shadow(0 0 0.75rem blue);
}
/* .unit-front{ */
  /* filter:opacity(.9) */
/* } */
/* .unit-front:hover{ */
  /* filter: opacity(1); */
/* } */
/* .unit-bg{ */
  /* filter: invert(1) brightness(0.5); */
  /* filter: grayscale(); */
/* } */
/* .unit-bg:hover{ */
  /* background-image: url(../assets/img/D-bg.png); */
  /* filter:blur(0)opacity(1); */
/* } */
.unit img{
  width: 100%;
}
</style>