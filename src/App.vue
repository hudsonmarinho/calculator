<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator />
  </div>
</template>

<script>
  import Calculator from "./main/Calculator"

  export default{
    components: {
      Calculator
    }
  }
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Roboto+Mono:100,300,400,500,700');

  *{
    font-family: 'Roboto Mono', monospace;
    font-weight: 100;
  }

  body{
    margin: 0;
  }

  #app{
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    background: linear-gradient(to right, rgba(83, 105, 118), rgb(41, 46, 73))
  }
</style>
