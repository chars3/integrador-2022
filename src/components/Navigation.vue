<template>
    <v-navigation-drawer
      expand-on-hover
      color="white"
      height="1fr"
    >
        <v-list-item>
            <v-list-item-title class="text-h6">
                <v-list-icon>
                    <v-icon color="#6515dd">mdi-currency-usd</v-icon>
                </v-list-icon>
                CMT Finance
            </v-list-item-title>
        </v-list-item>
        <v-list
          nav
          dense
        >
          <v-list-item link>
            <v-list-item-icon>
              <v-icon color="#6515dd">mdi-view-dashboard</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Dashboard</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon color="red">mdi-trending-down</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Despesas</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon color="green">mdi-trending-up</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Receitas</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon color="yellow">mdi-poll</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Investimentos</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon color="#2196f3">mdi-piggy-bank</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Metas</v-list-item-title>
          </v-list-item>
        </v-list>
    </v-navigation-drawer>
</template>

<script>
export default {
    name: 'app-navigation'
}
</script>