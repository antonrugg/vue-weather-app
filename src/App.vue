<template>
  <main>
    <div class="search-box">
      <input type="text" class="search-bar" placeholder="Search">
    </div>
  </main>
</template>

<script>


export default {
  name: 'App',
 data(){
   return{
     api_key: '327236b68a4458feac960c2ece88fa60'
   }
 }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body{
  font-family: 'Montserrat', sans-serif;
}

#app{
  background-image: url('./assets/cold-bg.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main{
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.25), rgba(0, 0, 0, 0.75));

}

.search-box{
  width: 100%;
  margin-bottom: 30px;
}

.search-box .search-bar{
  display: block;
  width: 100%;
  padding: 15px;
  color: #313131;
  font-size: 20px;
  appearance: none;
  border: none;
  outline: none;
  background: none;
  box-shadow: 0px 0px 16px rgba(0, 0 ,0, 0.25);
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 0px 16px 0px 16px;
  transition: 0.4s;

  &:focus{
    background-color: rgba(255, 255, 255, 0.75);
    box-shadow: 0px 0px 16px rgba(0, 0 ,0, 0.25);
    border-radius: 16px 0px 16px 0px;
  }
}



</style>
