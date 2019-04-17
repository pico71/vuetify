<template>
  <v-row justify="center">
    <v-time-picker v-model="picker"></v-time-picker>
  </v-row>
</template>

<script>
  export default {
    data () {
      return {
        time: null,
        landscape: false,
        ampmInTitle: false,
      }
    },
  }
</script>
