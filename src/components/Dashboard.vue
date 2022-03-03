<template>
  <div class="content">
    <h2 id="title">Dashboard</h2>
    <v-container fluid>

      <v-row class="ml-1">
        <v-col cols="6">
          <app-cardDespesas />
        </v-col>
        <v-col cols="6">
          <app-cardReceitas />
        </v-col>
      </v-row>

      <v-row class="ml-1">
        <v-col cols="6">
          <app-cardInvestimentos />
        </v-col>
        <v-col cols="6">
          <app-cardMetas />
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<style scoped>
.content {
  width: 100%;
  background-color: #edf3fb;
}

#title {
  margin: 15px 30px;
}

</style>
  
<script>
import CardDespesas from "./dashBoardComponents/CardDespesas.vue";
import CardInvestimentos from './dashBoardComponents/CardInvestimentos.vue';
import CardMetas from './dashBoardComponents/CardMetas.vue';
import CardReceitas from "./dashBoardComponents/CardReceitas.vue";

export default {
  name: "app-dashboard",
  components: {
    "app-cardDespesas": CardDespesas,
    "app-cardReceitas": CardReceitas,
    "app-cardInvestimentos": CardInvestimentos,
    "app-cardMetas": CardMetas,
  },
};
</script>
