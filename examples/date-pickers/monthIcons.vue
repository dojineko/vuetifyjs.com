<template>
  <v-layout row wrap>
    <v-flex xs12 sm6>
      <v-date-picker
        type="month"
        v-model="picker"
        year-icon="mdi-calendar-blank"
        prepend-icon="mdi-skip-previous"
        append-icon="mdi-skip-next"
      ></v-date-picker>
    </v-flex>
  </v-layout>
</template>

<script>
  export default {
    data () {
      return {
        picker: null
      }
    }
  }
</script>
