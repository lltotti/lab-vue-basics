<template>
 <!-- INTERACTION 1 -->
  <div id="app">
    <Header />
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav> -->
    <router-view/>
   <Footer />
  </div>
</template>


<script>
import Header from "./components/Header.vue";
import Footer from "@/components/Footer.vue";
export default {
  components:{
    Header,
    Footer
  }
  }



// export default {
//   name: 'HelloWorld',
//   props: {
//     msg: String
//   }
// }
</script>



<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
