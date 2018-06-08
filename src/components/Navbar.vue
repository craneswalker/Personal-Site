<template>
  <div id="Navbar" class="background-navy">
    <div id="title-container" class="background-yellow norwester-navy">
      <h1 class=" title-spacing">JACOB CRANE</h1>
      <h4 class=" title-spacing">front end developer</h4>
    </div>
    <nav>
      <ul>
        <li><a href="">Projects</a></li>
        <li><a href=""></a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
#Navbar {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
#title-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 50%;
  margin: 10px
}
</style>
