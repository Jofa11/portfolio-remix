<template>
  <div id="app">
    <vue-particles
      color="#dedede"
      :particle-opacity="0.7"
      :particles-number="80"
      shape-type="circle"
      :particle-size="4"
      lines-color="#dedede"
      :lines-width="1"
      :line-linked="true"
      :line-opacity="0.4"
      :lines-distance="150"
      :move-speed="3"
      :hover-effect="true"
      hover-mode="grab"
      :click-effect="true"
      click-mode="push"
    />
  </div>
</template>

<script>
import Vue from 'vue'
import VueParticles from 'vue-particles'
Vue.use(VueParticles)

export default {
    props: {
        color: {
            type: String,
            default: '#dedede',
        },
        particleOpacity: {
            type: Number,
            default: 0.7,
        },
        particlesNumber: {
            type: Number,
            default: 80
        },
        shapeType: {
            type: String,
            default: 'circle'
        },
        particleSize: {
            type: Number,
            default: 4
        },
        linesColor: {
            type: String,
            default: '#dedede'
        },
        linesWidth: {
            type: Number,
            default: 1
        },
        lineLinked: {
            type: Boolean,
            default: true
        },
        lineOpacity: {
            type: Number,
            default: 0.4
        },
        linesDistance: {
            type: Number,
            default: 150
        },
        moveSpeed: {
            type: Number,
            default: 3
        },
        hoverEffect: {
            type: Boolean,
            default: true
        },
        hoverMode: {
            type: String,
            default: 'grab'
        },
        clickEffect: {
            type: Boolean,
            default: true
        },
        clickMode: {
            type: String,
            default: 'push'
        }
    }
}
</script>

<style>

</style>