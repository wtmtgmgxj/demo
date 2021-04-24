<template>
  <q-page class="flex flex-center">

    <q-btn @click="hello" color="primary" label="Primary" />
    <countryDropDown label="Primarasy"></countryDropDown>


  </q-page>

</template>

<script>
  export default {
    name: 'PageIndex',
    data() {
      return {
        
      }
    },

    methods:
    {
      hello() {
        alert("hello");
      }
    },
    components: {
      "countryDropDown": require("components/search/CountryDropDown.vue").default
    }
  }
</script>
