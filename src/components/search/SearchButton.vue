<template>
  <div> <q-btn @click="search" color="primary" label="Search" /></div>
</template>

<script>
  import axios from 'axios'

  export default {
    name: '',
    methods:
    {
      search() {
        alert("I am In");
      },
      
    },
    async created() {
      try {
        const res = await axios.get("https://jsonplaceholder.typicode.com/todos/1")
        console.log(res)
      } catch (e) {
      console.error(e)}
    }
  }
</script>
