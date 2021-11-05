<template>
  <div class="hello">
    <div class="name">
      <div class="letter">
        <img src="../assets/img/m.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/n.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/o.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/p.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/q.jpeg">
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name {
  border: 1px solid red;
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: 100vh;
}
.letter{
  /* width: 100px;
  height: 800px; */
  margin: 10px;
  filter: drop-shadow(0px 0px 7px rgba(150, 150, 150, .7));
  max-width: 20%;
}
img {
  max-width: 20%;
}
</style>
