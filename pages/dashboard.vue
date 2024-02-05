<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <img src="https://home.chiraprawat.com/hos/img/logo4.png" width="400">
      </v-card>
      <v-card>
        <v-card-title class="headline">
          Welcome to Chira Care 
        </v-card-title>
        <v-card-text>

        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire"> END </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'dashboard',
}
</script>
