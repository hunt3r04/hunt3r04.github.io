<template>
  <div>
    <home/>
    <about/>
    <experience/>
    <contact/>
  </div>
</template>

<script>
import About from './views/About' //import the component
import Home from "./views/Home"; //import the component
import Experience from "./views/Experience"; //import the component
import Contact from "./views/Contact"; //import the component

export default {
  name: "App",
  components: {
    About  ,//instantiate it here
    Home,
    Experience,
    Contact
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400&display=swap');
*{
  padding: 0;
  margin: 0;
  font-family:'Montserrat', sans-serif;
}
</style>
