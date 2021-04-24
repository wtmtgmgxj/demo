<template>
  <div> <q-select v-model="model" :options="options" label="Category" /></div>
</template>

<script>
export default {
    name: 'CategoryDropDown',
    data() {
      return {
        model: null,
        options: ["BEDS", "REMDESIVIR"]
      }
    }
  }
</script>
