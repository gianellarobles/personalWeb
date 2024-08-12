<script lang="ts">
</script>

<template>
  <div>
    <h1>Portfolio</h1>
    <p>Here are some of my projects:</p>

    <img src="/folder-invoices.png" alt="Project 1" />

    <br>

    <img src="/folder-invoices.png" alt="Project 2" />

    <br>
    
    <img src="/folder-invoices.png" alt="Project 3" />
  </div>
</template>

<style scoped>  

/* This is for the mobile view */
img{
    margin-top: 35px;
   margin-left: 20px;
   height: 75px;
}

/* This is for the desktop view */
@media (min-width: 1024px) {
  img{
    margin-top: 35px;
    margin-left: 20px;
    height: 130px;
  }
}
</style>