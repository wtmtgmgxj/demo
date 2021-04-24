<template>
    <div class="q-pa-md">
      <q-table class="my-sticky-header-table"
               title="Treats"
               :data="data"
               :columns="columns"
               row-key="name"
               flat
               bordered />
    </div>
  </template>


<script>
  export default {
    data() {
      return {
        columns: [
          {
            name: 'category',
            required: true,
            label: 'Category',
            align: 'left',
            field: 'category',
            sortable: true
          },
          {name: 'country',align: 'center',label: 'Country',field: 'country', sortable: true},
          { name: 'city', label: 'City', field: 'city', sortable: true },
          { name: 'state', label: 'State', field: 'state', sortable: true },
          { name: 'village', label: 'Village', field: 'village', sortable: true },
          
          {
            name: 'info',
            label: 'Info',
            field: 'info',
            sortable: true
            //sort: (a, b) => parseInt(a, 10) - parseInt(b, 10)
          },
          { name: 'contact', label: 'Contact', field: 'contact', sortable: true },
         
        ],

        data: [
          {
            category: 'Frozen Yogurt',
            country: 'Frozen Yogurt',
            city: 'Frozen Yogurt',
            state: 'Frozen Yogurt',
            village: 'Frozen Yogurt',
            info: 159,
            contact: 6.0
          },
          {
            category: 'Frozen Yogurt',
            country: 'Frozen Yogurt',
            city: 'Frozen Yogurt',
            state: 'Frozen Yogurt',
            village: 'Frozen Yogurt',
            info: 159,
            contact: 6.0
          },
          {
            category: 'Frozen Yogurt',
            country: 'Frozen Yogurt',
            city: 'Frozen Yogurt',
            state: 'Frozen Yogurt',
            village: 'Frozen Yogurt',
            info: 159,
            contact: 6.0
          },
          {
            category: 'Frozen Yogurt',
            country: 'Frozen Yogurt',
            city: 'Frozen Yogurt',
            state: 'Frozen Yogurt',
            village: 'Frozen Yogurt',
            info: 159,
            contact: 6.0
          },
        ]
      }
    }
  }
</script>



