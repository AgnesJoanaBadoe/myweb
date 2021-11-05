<template>
  <div class="hello">
    <!-- These are the menu items -->
    <div class="menu">
      <div class="menu-item menu-text">
        Resume
        </div>
        <div class="menu-item menu-text">
          Well-being
        </div>
    <div class="menu-item menu-center">
      Agnes Joana
    </div>
      <div class="menu-item menu-text">
          YouTube
        </div>
        <div class="menu-item menu-text">
          About
        </div>
    </div>
    <!-- This is the div for the images on the web page -->
    <div class="name">
      <div class="letter">
        <img src="../assets/img/n.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/m.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/o.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/q.jpeg">
      </div>
      <div class="letter">
        <img src="../assets/img/p.jpeg">
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
/* This is the styling for the Home page */
.name {
  border: 1px;
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
  max-width: 105%;
}
/* This is the styling for the menu items */
.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.menu-item {
  flex: 1;
  /* border: 1px solid red; */
  text-align: center;
  /* font-size: 20px;
  color: #707070; */
}
.menu-text {
  font-size: 20px;
  color: #818181;
  padding: 10px;
  /* border: 2px solid blue; */
  cursor: pointer;
  border-bottom: 2px solid #080808;
  width: fit-content;

}
.menu-text:hover {
  /* color: #c278ff; */
  border-bottom: 2px solid #006994;
}
.menu-center {
  font-size: 36px;
  color: #EAEAEA;
}
</style>
