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
      <div class="unit">
        <img src="../assets/img/D.png"/>
      </div>
      <div class="unit">
        <img src="../assets/img/D.png"/>
      </div>
      <div class="unit">
        <img src="../assets/img/D.png"/>
      </div>
      <div class="unit">
        <img src="../assets/img/O.png"/>
      </div>
      <div class="unit">
        <img src="../assets/img/O.png"/>
      </div>
      <div class="unit">
        <img src="../assets/img/O.png"/>
      </div>
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
.menu-center{
  font-size: x-large;
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
  filter: invert(100);
}
.unit img{
  width: 100%;
}
</style>