<script setup lang="ts">

defineProps<{
  msg: string
}>()

</script>

<template>
  <div class="greetings">
 
    <h1 class="is-size-1 has-text-weight-normal has-text-white">{{ msg }} <span class="is-italic pink">Gianella</span></h1> 
   <h3>
  Feel free to browse through my personal website about my passions, projects, and resume.</h3>
<br>
<br>
  <img src="/Gianella.jpg">

  </div>
</template>

<style scoped>
/* this is the css for app */
img{
  height: 425px;
  width: 425px;
  border-radius: 50%;
  display: block;
  margin: auto;
  margin-top: -620px;
}

.greetings h1{
  text-align: center;
  margin-top: 575px;
}
.greetings h3 {
  text-align: center;
  
}

/* this is the css when full screen */ 
@media (min-width: 1024px) {
  .greetings h1{
    text-align: left;
    margin-top: 300px;
  }
  .greetings h3 {
    text-align: left;
  }
  img{
    margin-top: -275px;
    float: right;
  }
}
</style>
