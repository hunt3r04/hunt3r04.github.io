<template>
  <div class="home">
    <Navigation/>
    <div class="name-block">
      <div class="title-text">
        <h1>Bongani Muvimi</h1>
        <p>Juniour Frontend Developer</p>
      </div>
    </div>
  </div>
</template>
<script>
import Navigation from '../components/navigation';
export default {
  name:'Home',
  components:{
    Navigation
  }
}
</script>


<style scope>
  .home{
    background:url('../assets/img/bg.jpg') no-repeat;
    background-position: center;
    background-size: cover;
    height: 100vh;
    width: 100vw;
  }

  .name-block {
  display: flex;
  padding-top: 150px;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 80%;
  margin: 0 auto;
  z-index: 400;
}
.name-block   h1 {
    font-size: 2.3rem;
    padding: 3rem 3rem;
    text-align: center;
    text-transform: uppercase;
    border: 2px solid #fff;
    color: #fff;
    text-shadow:2px 2px 4px lightgray;
  }
.name-block   p {
    font-size: 1.5rem;
    text-align: center;
    margin: 5px auto;
    color: #fff;
    text-shadow:2px 2px 4px lightgray;
  }
  
</style>