<template>
  <v-app>
    <div>
      <v-toolbar dark>
        <v-toolbar-title>Conta</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-toolbar-items>
          <v-btn class="link" text router-link to="/cidades">
            Cidades
          </v-btn>
          <v-btn class="link" text router-link to="/agencias">
            Agências
          </v-btn>
          <v-btn class="link" text router-link to="/clientes">
            Clientes
          </v-btn>
        </v-toolbar-items>

      </v-toolbar>
    </div>
    <router-view></router-view>
  </v-app>
</template>
<style scoped>
</style>
