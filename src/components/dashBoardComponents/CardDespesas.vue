<template>
  <v-card class="pa-5" color="white" height="250px">
    <div class="despesas">
      <h2>Despesas</h2>
      <p>R$ 300,00</p>
    </div>
  </v-card>
</template>

<style scoped>
.despesas {
  text-align: center;
  color: #f44336;
}

.despesas p {
  font-size: 50px;
}
</style>


<script>
export default {
  name: "app-cardDespesas",
};
</script>