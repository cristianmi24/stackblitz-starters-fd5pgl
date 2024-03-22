<template>
  <v-container fluid>
    <v-row justify="center">
      <v-col cols="14">
        <v-card>
          <v-card-title class="bg-blue white--text">
            <span class="text-h4">Vlog</span>
          </v-card-title>
          <v-card-text class="text-center">
            <v-row justify="center">
              <v-col cols="2">
                <v-btn icon>
                  <v-icon>mdi-multimedia</v-icon>
                </v-btn>
                <div>Plantillas</div>
              </v-col>
              <v-col cols="2">
                <v-btn icon>
                  <v-icon>mdi-account-circle-outline</v-icon>
                </v-btn>
                <div>Vlogger Comunity</div>
              </v-col>
              <v-col cols="2">
                <v-btn icon>
                  <v-icon>mdi-bell</v-icon>
                </v-btn>
                <div>Notificacion</div>
              </v-col>
              <v-col cols="2">
                <v-btn icon>
                  <v-icon>mdi-help-circle</v-icon>
                </v-btn>
                <div>Ayuda</div>
              </v-col>
              <v-col cols="2">
                <v-btn icon>
                  <v-icon>mdi-medal-outline</v-icon>
                </v-btn>
                <div>Ranking</div>
              </v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.bg-blue {
  background-color: #2196f3;
}
</style>
