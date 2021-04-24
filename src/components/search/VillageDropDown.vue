<template>
  <div> <q-select v-model="model" :options="options" label="Village" /></div>

</template>

<script>
  export default {
    name: 'VillageDropDown',
    data() {
      return {
        model: null,
        options: ["Village1", "Village2"]
      }
    }
  }
</script>
