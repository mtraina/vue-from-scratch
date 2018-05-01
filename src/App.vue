<template>
    <div>
        <h1>App</h1>
        <HelloWorld/>
   </div>
</template>

<script>
   import HelloWorld from './components/HelloWorld'

   export default {
       name: 'App',
       components:{
           HelloWorld
       }
   }
</script>