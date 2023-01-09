<template>
  <div class="home">
    <div class="letters">
      <div class="unit">
        <img src="../assets/D.png"/>
      </div>
      <div class="unit">
        <img src="../assets/D.png"/>
      </div>
      <div class="unit">
        <img src="../assets/D.png"/>
      </div>
      <div class="unit">
        <img src="../assets/O.png"/>
      </div>
      <div class="unit">
        <img src="../assets/O.png"/>
      </div>
      <div class="unit">
        <img src="../assets/O.png"/>
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