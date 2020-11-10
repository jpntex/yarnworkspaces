<template>
  <v-app>
    <h1>Dashboard</h1>
    <Table />
  </v-app>
</template>

<script>
import { Table } from '@project/common'

export default {
  name: 'App',

  components: {
    Table,
  },

  data: () => ({
    //
  }),
};
</script>
