<template>

  <section id="content">
    <Header />
    <Banner />
    <About />
    <Services />
    <Team />
    <Footer />
    <Arrow />
  </section>

</template>

<script>
import Header from './components/Header'
import Banner from './components/Banner'
import About from './components/About'
import Services from './components/Services'
import Team from './components/Team'
import Footer from './components/Footer'
import Arrow from './components/Arrow'


export default {
  name: 'App',
  components:{
    Header,
    Banner,
    About,
    Services,
    Team,
    Footer,
    Arrow
  }
}

</script>



<style>

*{
  margin: 0;
	padding: 0;
	box-sizing: border-box;
	outline: none;
	list-style: none;
	text-decoration: none;
	scroll-behavior: smooth;
  font-family: 'Grandstander', cursive;
}

</style>
