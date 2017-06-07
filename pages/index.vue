
<template>

  <section class="container">
  <div class="separator"></div>
    <div>
      
      
      <h2 class="subtitle">
        I'm <span>James Zaccardo</span>, a frontend developer & UX/UI designer based in <span>Los Angeles</span>.
        
        
      </h2>
      
    </div>
  </section>
</template>

<script>
import Logo from '~components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css?family=Quicksand');

h2 span {
  color: #2196f3;
}

.white-bg {
    background-color: blue;
}

.vertical-line {
    width: 1px;
    height: 200px;
    opacity: .5;
    display: inline-block;
}

.separator {
    width: 100%;
    height: 400px;
    margin-top: -210px;
    background-color: gold;
    transform: skewY(15deg);
        z-index: -1;
    position: absolute;
}


.container
{
  min-height: 100vh;
  display: flex;
  width: 960px;
  
  justify-content: left;
  align-items: left;
  text-align: left;
}
.title
{
  font-family: 'Quicksand', sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-family: 'Quicksand', sans-serif;
  font-weight: 700;
  font-size: 53px;
  color: whitesmoke;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
