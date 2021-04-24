<template>
  <div>
    <q-select v-model="model" :options="options" label="Country"  />
  </div>
</template>

<script>
  export default {
    name: 'CountryDropDown',
    data() {
      return {
        model: null,
        options: ["India", "USA"]
      }
    }
  }
</script>
