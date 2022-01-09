<template>
  <div class="card-container">
    <div class="card">
      <a
    
        href="https://send-my-verse.herokuapp.com/"
        target="_blank"
      >
        <h2>My Verse</h2>
        <h5>Description</h5>
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
        <h2>Megslist</h2>
        <h5>Description</h5>
        <img
          src="../assets/megslist.png"
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
    width: 11em;
    height: 6em;
}

.card-container {
    padding: 2em;
}

.card {
    margin: auto;
    width: 15em;
    height: auto;
    border: 5px solid rgb(66, 22, 77);
    border-radius: 10%;
    background-color: rgba(157, 63, 157, 0.5);
    margin-bottom: 2em;
}

.card:hover {
    border: 7px solid rgb(66, 22, 77);
    background-image: linear-gradient(rgba(92, 68, 112, .9), rgba(248, 73, 219, .9));
}
</style>