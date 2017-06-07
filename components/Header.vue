<template>
    <header>
     
    </header>
</template>
<style>
ul {
  display: flex;
  list-style: none;
  border: 1px solid black;
  
}
li {
  flex: 0 0 auto;
  background: black;
  height: 40px;
  width: 10%;
  padding: 10px;
  margin: 0 3px;
  color: white;
  text-align: center;
}
li:nth-child(1) {
  margin-right: auto;
  padding-left: 10px;
}
header {
    z-index: 1000;
    position: fixed;
    width: 100%;
    top: 30px;
    transition: top 0.2s ease-in-out;
}

</style>
