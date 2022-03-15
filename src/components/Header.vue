<template>
    <header class="head">
        <div class="mini-head">
            <img src="../assets/images-icons/logos/circle.svg">
             
            
             <nav>
              <router-link to="/">Home</router-link> |
              <router-link to="/projects">Projects</router-link> |
              <router-link to="/services">Services</router-link>
            </nav>
            
         </div>
    </header>
   
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.mini-head{
    /* position: absolute; */
    max-width: 1100px;
    margin-left: auto;
    margin-right:auto;
    /* margin-top: 70px; */
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    /* border: 1px solid saddlebrown;   */
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
