<template>
  <v-footer padless color="#6515dd">
    <v-col
      class="text-center"
      cols="12"
    >
      <p>{{ new Date().getFullYear() }} — <strong>CMT Finance</strong></p>
    </v-col>
  </v-footer>
</template>

<style scoped>
  p {
    color: #fff;
  }
</style>

<script>
export default {
    name: 'app-footer'
}
</script>