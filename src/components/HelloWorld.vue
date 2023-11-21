<template>
  <div class="background-container">
    <h1>TaskSync PRO</h1>
    <h2>Sync task with ease, enpower your productivity</h2>
  </div>
</template>

<script lang="ts">
import { Vue } from "vue-class-component";

export default class HelloWorld extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Monoton&family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
h1 {
  color: aliceblue;
  font-size: 4rem;
  font-weight: 900;
  font-family: "Montserrat", sans-serif;
  text-align: left;
  padding: 20px;
}
h2 {
  font-size: 2.5rem;
  font-weight: 800;
  position: absolute;
  bottom: 20px;
  padding: 20px;
  border-radius: 10px;
  -webkit-background-clip: text;
  color: #e0eeeb;
  width: fit-content;
  max-width: 50%;
  right: 10px;
  backdrop-filter: blur(4px);
  text-align: center;
}
.background-container {
  background-image: url("../assets/taskSyncMonkey.png");
  background-size: cover; /* Adjust this to your preference */
  background-position: center; /* Adjust this to your preference */
  background-repeat: no-repeat; /* Adjust this to your preference */
  width: 100%;
  height: 100vh;
  position: relative;
}
</style>
