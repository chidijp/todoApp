<template>
  <div id="app">
    <Todos v-bind:todos="todos"/>
  </div>
</template>

<script>

import Todos from './components/Todos';
export default {
  name: 'app',
  components: {
   Todos

  },
  data(){
      return{
        todos:[
          {
            id:1,
            title:"todo 1",
            completed:true
          },
          {
            id:2,
            title:"todo 2",
            completed:false
          },
          {
            id:3,
            title:"todo 3",
            completed:true
          }
        ]
      }
    }
}
</script>

<style>

</style>
