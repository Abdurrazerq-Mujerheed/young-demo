<template>
  <v-footer fixed>
    <v-col class="text-center">©️{{year()}}</v-col>  
  </v-footer>
</template>

<script>
export default {
  mounted() {
    this.year
  },
  methods: {
    year() {
      let date = new Date()
      return date.getFullYear()
    }
  }
}
</script>