<template>
  <div> <q-select v-model="model" :options="options" label="City" /></div>

</template>

<script>
  export default {
    name: 'CountryDropDown',
    data() {
      return {
        model: null,
        options: ["City1", "City2"]
      }
    }
  }
</script>
