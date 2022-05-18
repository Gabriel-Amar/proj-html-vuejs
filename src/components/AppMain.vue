<template>
  <div>
        <button class="btn rounded-circle btn-danger" 
        @click="scrollToTop()"> <i class="fa-solid fa-angle-up"></i></button>
        <div class="container-fluid">
          <div class="row">
            <div class="col-lg-3">
              <div class="wrapper">
                <!-- <div class="layover">
                  <i class="fas fa-plus"></i>
                </div> -->
                <img v-img:group src="https://baconmockup.com/800/400" class="img-fluid" alt="">
              </div>
            </div>

            <div class="col-lg-3">
              <div class="wrapper">
                <!-- <div class="layover">
                  <i class="fas fa-plus"></i>
                </div> -->
                <img v-img:group src="https://placekitten.com/800/400" class="img-fluid" alt="">
              </div>
            </div>
            <div class="col-lg-3">
              <div class="wrapper">
                <!-- <div class="layover">
                  <i class="fas fa-plus"></i>
                </div> -->
                <img v-img:group src="https://www.fillmurray.com/800/400" class="img-fluid" alt="">
              </div>
            </div>
            <div class="col-lg-3">
              <div class="wrapper">
                <!-- <div class="layover">
                  <i class="fas fa-plus"></i>
                </div> -->
                <img v-img:group src="https://placebear.com/800/400" class="img-fluid" alt="">
              </div>
            </div>
          </div>
          </div>

        </div>
 
</template>

<script>
import Vue from 'vue';
import VueImg from 'v-img';

Vue.use(VueImg);
export default {
  name: 'AppMain',
  methods: {
        scrollToTop() {
            window.scrollTo(0, 0);
        },
        }
}
</script>

<style scoped lang="scss">
@import "../assets/style/general.scss";
@import "../assets/style/vars.scss";

button{
  position: fixed;
  bottom: 50px;
  right: 50px;
  z-index: 99;
    background: $ac-salmon !important;
    padding: 8px 12px;
    color: #fff;
    cursor: pointer;
    height: 56px;
    width: 56px;
}




.wrapper{
  position: relative;
}
.wrapper:hover .layover{
  background-color: rgba(26, 188, 156, 0.7);
  border-radius: 5px;
}
.wrapper:hover .layover i.fa-plus{
  display: block;
}
.layover{
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100%;
}
.layover i.fa-plus{
  position: absolute;
  display: none;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 70px;
  color: white;
}
img{
  width: 452px;
  height: 234px !important;
  margin-top: 50px;
}
</style>
