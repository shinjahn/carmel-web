<template>
    <div class="headerbackground-image">
      <div class="headertext-overlay">
        <h1>Carmel Fellowship</h1>
        <h3>New York and New Jersey</h3>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomeHeader'
  }
  </script>
  
  <style scoped>
  .headerbackground-image {
    background-image: url('../assets/cross.webp');
    background-size: cover; 
    background-position: center;
    min-height: 300px; 
    display: flex;
    align-items: center;
    padding: 10px;
    justify-content: center;
    margin-bottom: 10px;
    margin-left: 10px;
  }

  .headertext-overlay {
  text-align: left;
  color: blue;
  font-family: calligraphy;
  font-style: italic;
  font-size: 30px;
  line-height: 40px;
  text-align: center;
  margin-top: 20px;
  margin-bottom: 10px;
  }

  </style>