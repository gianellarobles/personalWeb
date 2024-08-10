<script setup lang="ts">
defineProps<{
  msg: string
}>()

</script>

<template>
  <div class="greetings">
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <h1 class="is-size-1 has-text-weight-normal has-text-white">{{ msg }} <span class="is-italic pink">Gianella</span></h1> 
   <h3>
  Feel free to browse through my personal website about my passions, projects, and resume.</h3>
    
  </div>
</template>

<style scoped>

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;

  }
}
</style>
