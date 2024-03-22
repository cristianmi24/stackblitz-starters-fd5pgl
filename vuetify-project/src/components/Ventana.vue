<template>
  <v-card color="grey-lighten-4" height="100px" rounded="0" flat>
    <v-toolbar density="compact">
      <v-btn icon>
        <v-icon>mdi-account-cog-outline</v-icon>
      </v-btn>

      <v-toolbar-title>Search</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-camera</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-open-source-initiative</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-door</v-icon>
      </v-btn>
    </v-toolbar>
    <v-img
      :width="110"
      aspect-ratio="1/9"
      cover
      src="https://static.vecteezy.com/system/resources/previews/025/065/369/non_2x/vlog-logo-flat-style-illustration-of-vlog-free-vector.jpg"
    ></v-img>
  </v-card>
</template>
