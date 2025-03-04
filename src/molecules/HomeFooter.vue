<template>
    <div class="homefooter-grid-container">
      <div class="homefooter-grid-text1">
        <h3>Join us each Sunday!</h3>
        <p>10:00 am</p>
      </div>
      <div class="homefooter-grid-text2">
        <p>56 Burda Ave.</p>
        <p>New City, NY 10956</p>
        <p>(646) 398-0348</p>
        <p>carmelfellowshipnj@gmail.com</p>
      </div>
    </div>
   
</template>
    
<script>
    export default {
      name: 'HomeFooter'
    }
</script>
    
    
<style scoped>
  
.homefooter-grid-container {
      display: grid;
      grid-template-columns: 450px 500px;
      border: 1px solid gray;
      padding: 5px;
      margin-left: 12px;
    }
  
.homefooter-grid-text1 {
      text-align: left;
      color: darkblue;
      font-size: 20px;
      font-weight: bold;
      line-height: 10px;
      justify-content: top left;
      padding: 2px;
      margin-top: 2px;
      margin-left: 150px;
    }

.homefooter-grid-text2 {
      text-align: left;
      color: darkblue;
      font-size: 20px;
      font-weight: bold;
      line-height: 5px;
      justify-content: top left;
      padding: 2px;
      margin-top: 2px;
      margin-left: 100px;
    }
   
</style>