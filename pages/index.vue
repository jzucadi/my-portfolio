
<template>
  <section class="container">
    <div>
      
      
      <h2 class="subtitle">
        I'm <span>James Zaccardo</span>, a frontend developer & UX/UI designer based in Los Angeles.
        <div class="separator"></div>
        <div class="vertical-line white-bg"></div>
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

h2 span {

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
    width: 50px;
    height: 2px;
    margin-top: 150px;
    background-color: #93e2f2;
}
.container
{
  min-height: 100vh;
  display: flex;
  margin: 5%;
  justify-content: left;
  align-items: left;
  text-align: left;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  font-weight: 700;
  font-size: 62px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
