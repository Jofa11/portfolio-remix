<template>
  <div class="card-container">
    <h3 id="projects">Projects</h3>
    <div class="card">
      <a
    
        href="https://unruffled-rosalind-0724d0.netlify.app/"
        target="_blank"
      >
        <h2>Creativity Canvas</h2>
        <h5>A drawing app built using Vue.js for a hackathon</h5>
        <img
          src="../assets/art-app.png"
          alt="project landing page"
        >
      </a>
    </div>
    <div class="card">
      <a
    
        href="https://send-my-verse.herokuapp.com/"
        target="_blank"
      >
        <h2>My Verse</h2>
        <h5>A MERN stack project using vanilla CSS</h5>
        <img
          src="../assets/my-verse-home.png"
          alt="project landing page"
        >
      </a>
    </div>
    <div class="card">
      <a
    
        href="https://themegslist.herokuapp.com/"
        target="_blank"
      >
        <h2>The MegsList</h2>
        <h5>A marketplace app. MERN stack with Redux</h5>
        <img
          src="../assets/megslist-2.png"
          alt="project landing page"
        >
      </a>
    </div>
    <div class="card">
      <a
    
        href="https://gentle-reaches-48748.herokuapp.com/"
        target="_blank"
      >
        <h2>X Trainer</h2>
        <h5>A full stack project using React and Django</h5>
        <img
          src="../assets/x-trainer-2.png"
          alt="project landing page"
        >
      </a>
    </div>
    <div class="card">
      <a
    
        href="https://project-two-guitar-app.herokuapp.com/"
        target="_blank"
      >
        <h2>Guitar Chord App</h2>
        <h5>A React project that accesses a third party API</h5>
        <img
          src="../assets/guitar.png"
          alt="project landing page"
        >
      </a>
    </div>
    <div class="card">
      <a
    
        href="https://jofa11.github.io/trivia-project/"
        target="_blank"
      >
        <h2>Star Wars Trivia</h2>
        <h5>A game built using vanilla Javascript, HTML, and CSS</h5>
        <img
          src="../assets/vader.png"
          alt="project landing page"
        >
      </a>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
img {
    width: 10em;
    height: 6em;
    border: 2px solid rgb(66, 22, 77);
    border-radius: 5%;
}

a {
    text-decoration: none;
}

h2 {
    padding: 2% 5%;
    color: rgb(66, 22, 77);
}

h5 {
    padding: 2% 10%;
    color: rgb(66, 22, 77);
}

.card-container {
    padding: 2em;
    
}

.card {
    margin: 10%;
    width: 15em;
    height: auto;
    border: 5px solid rgb(66, 22, 77);
    border-radius: 10%;
    background-color: rgba(157, 63, 157, 0.5);
    margin-bottom: 2em;
    display: inline-block;
    justify-content: space-between;
    box-shadow: 4px 4px 5px 2px rgb(83, 39, 124);
}

#projects {
  padding-top: 2%;
  padding-bottom: 1%;
}

.card:hover {
    border: 5px solid rgb(129, 45, 150);
    background-image: linear-gradient(rgba(92, 68, 112, .9), rgba(248, 73, 219, .9));
    box-shadow: 5px 5px 5px 2px rgb(144, 76, 208)
}

@media (min-width: 1000px) {
    .card {
        margin: 5%;
    }
}

@media (min-width: 1700px) {
    .card {
        margin: 8%;
    }
}
</style>