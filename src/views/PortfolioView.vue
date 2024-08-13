<script lang="ts">
</script>

<template>
  <div>
    <h1>Portfolio</h1>
    <p>Here are some of my projects:</p>

  
    <a href="https://cs.newpaltz.edu/p/s24-02/v2/index.php">
    <img src="/folder-invoices.png" alt="Project 1" />
      </a>
      <h3>OS Visuals</h3>
      <h5>hi</h5>
      
    <br>


    <a href="https://healing-fitness.onrender.com/">
    <img src="/folder-invoices.png" alt="Project 2" />
      </a>
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
h3{
  margin-top: -100px;
  margin-left: 200px;
  font-size: 20px;
}

/* This is for the desktop view */
@media (min-width: 1024px) {
  img{
    margin-top: 70px;
    margin-left: 20px;
    height: 150px;
  }
  h3{
  margin-top: -120px;
  margin-left: 200px;
  font-size: 23px;

}
h5{
  margin-top: -5px;
  margin-left: 200px;
  font-size: 15px;
}
}
</style>