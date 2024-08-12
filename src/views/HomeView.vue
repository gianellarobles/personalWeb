<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="greetings">

    <h1 class="has-text-weight-normal has-text-white">Welcome, I'm <span class="is-italic pink">Gianella</span>
    </h1>
    <h3>
      Feel free to browse through my personal website about my passions, projects, and resume.</h3>
    <br>
    <br>
    <img src="/Gianella.jpg">

  </div>
</template>

<style scoped>
/* this is the css for app */
img {
  height: 250px;
  width: 240px;
  border-radius: 50%;
  display: block;
  margin: auto;
  margin-top: -425px;
}

.greetings h1 {
  text-align: center;
  margin-top: 400px;
  font-size: 3em;
}

.greetings h3 {
  text-align: center;
  font-size: 1em
}

/* this is the css when full screen */
@media (min-width: 1024px) {
  .greetings h1 {
    font-size: 4.2em;
    text-align: left;
    margin-top: 300px;
  }

  .greetings h3 {
    text-align: left;
    font-size: 1.2em
  }

  img {
    margin-top: -275px;
    float: right;
    height: 425px;
    width: 410px;
  }
}
</style>