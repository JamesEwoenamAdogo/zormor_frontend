<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class="nav-bar">
   <div style="cursor: pointer;">Add Location</div>
   <div style="cursor: pointer;">All Locations</div>
  </div>
 
  <div class="add-location-input">
    <input type="text" placeholder="name">
    <textarea name="" id="" cols="5" placeholder="description of place" rows="5"></textarea>
    <input type="text" placeholder="location">
    <label>Open Hours</label>
    <div class="sub-input">
      
      <h3>From</h3><input type="time" placeholder="open hours">
      <h3>To</h3><input type="time" placeholder="open hours">


    </div>
   
    <input type="file">



  </div>

 
</template>

<style scoped>

.nav-bar{
  display: flex;
  position:absolute;
  top:1%;
  left:40%;
  color:white;
  font-size: 1.6rem;

  gap:40px;
  
  
}

.add-location-input{
  display:flex;
  flex-direction: column;
  gap: 15px;
  position: absolute;
  left:40%;
  top: 30%;
}
.sub-input{
  width:400px;
  display: flex;
  gap:30px;
}

.nav-bar div{

  
}

input{
  width: 400px;
  border-radius: 5px;
  height: 30px;
}



@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  
}
</style>
