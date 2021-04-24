<template>
  <q-page padding>
    <!-- content -->
    <categoryDropDown></categoryDropDown>
    <countryDropDown></countryDropDown>
    <cityDropDown></cityDropDown>
    <stateDropDown></stateDropDown>
    <villageDropDown></villageDropDown>
    <searchButton></searchButton>

    <br>

    <searchResultsTable></searchResultsTable>

  </q-page>
</template>

<script>
export default {
    components: {
    "countryDropDown": require("components/search/CountryDropDown.vue").default,
    "cityDropDown": require("components/search/CityDropDown.vue").default,
    "categoryDropDown": require("components/search/CategoryDropDown.vue").default,
    "stateDropDown": require("components/search/StateDropDown.vue").default,
    "villageDropDown": require("components/search/VillageDropDown.vue").default,
    "searchResultsTable": require("components/search/SearchResultsTable.vue").default,
    "searchButton": require("components/search/SearchButton.vue").default,

    },
    

}
</script>
