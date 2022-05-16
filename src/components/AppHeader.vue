<template>
  <div>
    <nav class="navbar navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="../assets/img/Logo.jpg" alt="Academy logo" class="d-inline-block align-text-top">
    </a>
    <ul>
      <li v-for="(item,index) in links" :key="index">
        {{item.testo}}
      </li>
    </ul>
  </div>
</nav>
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  data(){
    return{
      links: [
        {
          testo: "Home",
          link: "",
          active: false,
        },
        {
          testo: "About",
          link: "",
          active: false,
        },
        {
          testo: "Academics",
          link: "",
          active: false,
        },
        {
          testo: "Courses",
          link: "",
          active: false,
        },
        {
          testo: "News",
          link: "",
          active: false,
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";

nav{
  ul {
  display: flex;
  margin-bottom: 0;
  padding: 10px;
  list-style-type: none;
  gap: 30px;
  cursor: pointer;
  font-weight: bold;
  }
}
.container{
  align-items: baseline !important;
  padding: 8px !important;
}
img{
  width: 120px;
  position: absolute;
  height: 100px;
  top: 0;
  z-index: 99999;
}
</style>
