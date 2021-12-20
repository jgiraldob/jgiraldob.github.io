<template>
  <div class="profile container-fluid">
    <Nav></Nav>
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Nav,
    Header, 
    Main, 
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#app .profile {

}
</style>
