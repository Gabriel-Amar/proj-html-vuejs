<template>
  <div>
    <nav class="navbar navbar-light bg-light">
  <div class="container ">
    <div class="navbar-brand" href="#">
      <img src="../assets/img/Logo.jpg" alt="Academy logo" class="d-inline-block align-text-top">
    </div>
    <ul>
      <b-dropdown id="dropdown-1"  size="sm" text="Dropdown" variant="transparent" class="fw-bold">
    <b-dropdown-item>First Action</b-dropdown-item>
    <b-dropdown-item>Second Action</b-dropdown-item>
    <b-dropdown-item>Third Action</b-dropdown-item>
  </b-dropdown>
      <li v-for="(item,index) in links" :key="index">
        <a href="#">{{item.testo}}</a>
      </li>
    </ul>


    
  </div>
</nav>
  </div>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
Vue.use(BootstrapVue)
Vue.use(IconsPlugin)
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
@import "../assets/style/vars.scss";


nav{
  ul {
  display: flex;
  margin-bottom: 0;
  padding: 10px;
  list-style-type: none;
  gap: 30px;
  align-items: center;
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
li{
  position: relative;
}
a:after {    
  background: none repeat scroll 0 0 transparent;
  bottom: 0;
  content: "";
  display: block;
  height: 2px;
  right: 0%;
  position: absolute;
  background: $ac-salmon;
  transition: width 0.3s ease 0s, left 0.3s ease 0s;
  width: 0;
}
a:hover:after { 
  width: 50%; 
  right: 0; 
}
a{
  color: $ac-black;
  text-decoration: none;
}
a:hover{
  color: black;
}

</style>
