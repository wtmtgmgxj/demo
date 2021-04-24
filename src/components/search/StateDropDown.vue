<template>
  <div> <q-select v-model="model" :options="options" label="State" /></div>

</template>

<script>
  export default {
    name: 'CountryDropDown',
    data() {
      return {
        model: null,
        options: ["State1", "State2"]
      }
    }
  }
</script>
