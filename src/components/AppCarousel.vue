<template>
  <div>
    <b-carousel
      
      id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
      v-model="slide"
      :interval="4000"
      controls
      
      background="#ababab"
      img-width="1024"
      img-height="480"
      
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      

      <!-- Slides with custom text -->
      <b-carousel-slide
        caption="First slide"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
        img src="../assets/img/02_Landing-Page.jpg"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
        <h1>Hello world!</h1>
      </b-carousel-slide>

      

      
    </b-carousel>

    
  </div>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
  export default {
      name: "AppCarousel",
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart() {
        this.sliding = true
      },
      onSlideEnd() {
        this.sliding = false
      }
    }
  }
  Vue.use(BootstrapVue),
  Vue.use(IconsPlugin)
</script>