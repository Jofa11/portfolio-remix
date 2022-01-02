<template>
  <nav>
    <ul>
      <li>
        <a
          href="mailto: favrejoshua@yahoo.com"
          target="_blank"
        ><img
          src="../assets/email.png"
          alt="email icon"
        ></a>
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/joshua-favre/"
          target="_blank"
        ><img
          src="../assets/linkedin.png"
          alt="linkedin icon"
        ></a>
      </li>
      <li>
        <a
          href="https://www.facebook.com/joshua.favre.3/"
          target="_blank"
        ><img
          src="../assets/facebook.png"
          alt="facebook icon"
        ></a>
      </li>
      <li>
        <a
          href="https://www.instagram.com/favrejoshua/"
          target="_blank"
        ><img
          src="../assets/instagram.png"
          alt="instagram icon"
        ></a>
      </li>
      <li>
        <a
          href="https://twitter.com/FavreJoshua"
          target="_blank"
        ><img
          src="../assets/twitter.png"
          alt="twitter icon"
        ></a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
}
</script>


<style scoped>
nav {
  background-color: rgba(92, 68, 112, 0.7);
}

ul {
  margin: 0;
  padding: 0;
}

li {
  list-style-type: none;
  display: inline;
  padding: .2em;
  
}

li:hover {
  background-image: linear-gradient(rgba(92, 68, 112, .9), rgba(248, 73, 219, .9));
  border: 2px solid rgb(66, 22, 77);
  border-radius: 10%;
  /* border-radius: 50%;  */
}

@media (min-width: 500px) {
  nav {
    height: 5em;
  }

  li {
    float: right;
  }
}
</style>
