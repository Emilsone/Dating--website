<template>
  <div id="app">
    <Nav class="" />
    <Banner />
    <Welcome />
    <Profile />
    <Provide />
    <Footer />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Banner from './components/Banner.vue'
import Welcome from './components/Welcome.vue'
import Profile from './components/Profile.vue'
import Provide from './components/Provide.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Nav,
    Banner,
    Welcome,
    Profile,
    Provide,
    Footer
  }
}
</script>
<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
#app{
  font-family: 'Poppins', sans-serif;
  font-weight: 300;
	font-size:16px;
}
</style>
