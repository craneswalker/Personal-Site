<template>
  <div id="App">
    <Navbar/>
    <Jumbotron/>
    <Projects/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import Jumbotron from '@/components/Jumbotron'
import Projects from '@/components/Projects'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    Projects
  }
}
</script>

<style>
@font-face {
    font-family: norwester;
    src: url(assets/fonts/norwester.otf);
}
#App{
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.norwester-white {
  color: white;
  font-family: norwester;
}
.background-navy {
  background: rgb(50,76,104);	  
}
.norwester-navy {
  color:  rgb(50,76,104);	
  font-family: norwester; 
}
.background-yellow {
  background: rgb(255,206,0);  
}
.norwester-yellow {
  color:  rgb(255,206,0);
  font-family: norwester;
}
.title-spacing {
  letter-spacing: 10px;
}
.no-margin {
  margin: 0px;
}
</style>
