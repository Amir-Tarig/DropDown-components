<template>
 <header>
   <Navbar/>
 </header>
</template>

<script>
import Navbar from './components/NavBar'


export default {
  name: 'App',
  components: {
   Navbar,
  }
}
</script>

<style>

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body{
  font-family: 'montserrat',sans-serif;

}

header{
  width:100vw;
  background-color: #222;
  padding: 15px;
}
</style>
