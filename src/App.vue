<template>
<div>
  <h1>directivas en vue.js</h1>
<hr />
<h2>v.text</h2>
<span  v-text="'hola desde la directiva v-text'"></span>
<br>
<span>Hola desde la directiva v-text</span>
<br>
<span v-text="titulo"></span>
<br>
esta es una transmutacxion de texto con una variable prop <br>
{{titulo}}
</div>
</template>
<script>
  export default{
    data:() => ({
      titulo:"hola desde vue.js",
    }),
  }
</script>
<style scoped>
div{
  text-align: center;
   margin: 0px 2rem;
}
</style> 