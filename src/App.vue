<template>
  <div id="app">
    <h1>Hello There</h1>
    <h3 id="myName">My name is Joshua Favre and I create software.</h3>
    <Particles
      id="tsparticles"
      :particles-init="particlesInit"
      :particles-loaded="particlesLoaded"
      :options="{
        background: {
          color: {
            value: 'rgb(202, 162, 245)'
          },
          opacity: {
            value: 0.4
          }
        },
        fpsLimit: 60,
        interactivity: {
          events: {
            onClick: {
              enable: true,
              mode: 'push'
            },
            onHover: {
              enable: true,
              mode: 'repulse'
            },
            resize: true
          },
          modes: {
            bubble: {
              distance: 400,
              duration: 2,
              opacity: 0.8,
              size: 40
            },
            push: {
              quantity: 4
            },
            repulse: {
              distance: 200,
              duration: 0.4
            }
          }
        },
        particles: {
          color: {
            value: '#dabef7'
          },
          //links: {
          //color: '#dabef7',
          //distance: 150,
          //enable: true,
          //opacity: 0.5,
          //width: 1
          //},
          collisions: {
            enable: true
          },
          move: {
            direction: 'none',
            enable: true,
            outMode: 'bounce',
            random: false,
            speed: 3,
            straight: false
          },
          number: {
            density: {
              enable: true,
              area: 800
            },
            value: 80
          },
          opacity: {
            value: 0.5
          },
          shape: {
            type: 'star'
          },
          size: {
            random: true,
            value: 5
          },
        },
        detectRetina: true
      }"
    />
    <div>
      <Header />
      <!-- <button @click="toggleTheme">
        dark
      </button> -->
      <ProjectCard />
      <Profile />
      <GithubApi />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Profile from './components/Profile.vue';
import ProjectCard from './components/ProjectCard.vue';
import GithubApi from './components/GithubApi.vue';

export default {
  name: 'App',
  data() {
    return {
      theme: 'light'
    }
  },
  components: {
    Header,
    Profile,
    ProjectCard,
    GithubApi
  },
  methods: {
    toggleTheme() {
      const bod = document.getElementsByName('body');
      console.log(bod);
      bod.style = '{ background: url(../src/assets/dark-background.jpeg) }';
      // const hd3 = document.querySelectorAll('h3');
      // // if (this.theme === 'light') {
      //   hd3.style = '{ color: rgb(98, 237, 24) }';
      //   this.theme = 'dark';
      // }
      
    }
  }
}
</script>

<style>
html,
body {
  width: 100%;
  height: 100%;
  margin: 0px;
  padding: 0px;
  overflow-x: hidden;
  background: url('../src/assets/prpbkg.jpeg') no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

#myName {
  font-size: 3em;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
