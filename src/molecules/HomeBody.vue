<template>
  <div class="homebody-grid-container">
    <div class="homebody-image1">  
      <div class="homebody-overlay-text1">
        <h4>Our Mission</h4>
        <p>Carmel Fellowship is a church community of believers whose purpose is to worship the living God who sent Jesus Christ to save us and to have fellowship with us, and to share the gospel from our neighborhoods to the ends of the earth.</p>
      </div>
    </div>

    <div class="homebody-image2">  
      <div class="homebody-overlay-text2">
        <h4>Our Beliefs</h4>
        <p>We believe in one God existing in three persons: Father, Son, and Holy Spirit.</p>
        <p>Salvation is the free gift of God, entirely apart from works, and is possessed by all who by faith received the Lord Jesus Christ as their personal Savior.</p>
      </div>
    </div>
  </div>
</template>
    
<script>
  export default {
    name: 'HomeBody'
  }
</script>
        
<style scoped>
  
.homebody-grid-container {
  display: grid;
  grid-template-columns: 300px 713px;
  padding: 5px;
}

.homebody-image1 {
  background-image: url('../assets/sky.jpg');
  background-size: cover; 
  background-position: center; 
  min-height: 600px; 
  display: flex;
  margin-bottom: 20px;
  margin-top: 5px;
  margin-left: 5px;
  justify-content: center;
}

.homebody-overlay-text1 {
  text-align: left;
  color: darkblue;
  font-size: 20px;
  line-height: 20px;
  justify-content: top left;
  padding: 5px;
  margin-top: 5px;
  margin-left: 5px;
  margin-right: 10px;
}

.homebody-image2 {
  background-image: url('../assets/sky.jpg');
  background-size: cover; 
  background-position: center; 
  min-height: 600px; 
  display: flex;
  margin-bottom: 20px;
  margin-top: 5px;
  margin-left: 5px;
  justify-content: center;
}

.homebody-overlay-text2 {
  text-align: left;
  color: darkblue;
  font-size: 20px;
  line-height: 20px;
  justify-content: top left;
  padding: 5px;
  margin-top: 5px;
  margin-left: 50px;
  margin-right: 50px;
}
</style>