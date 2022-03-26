<template>
  <div>
    <!-- <h1>{{ info.login }}</h1> -->
    <p>{{ info }}</p>
  </div>
</template>

<script>
import axios from 'axios';

export default {
    created() {
        axios.get("https://api.github.com/users/jofa11")
        .then((res) => {
            console.log(res);
            this.info = res.data;
            console.log(res.data);
        })
    }
}
</script>

<style>

</style>