<template>
  <v-sheet class="mx-auto" elevation="8" max-width="800">
    <v-slide-group
      v-model="model"
      class="pa-4"
      selected-class="bg-primary"
      multiple
      show-arrows
    >
      <v-slide-group-item
        v-for="n in 15"
        :key="n"
        v-slot="{ isSelected, toggle, selectedClass }"
      >
        <v-card
          :class="['ma-4', selectedClass]"
          color="grey-lighten-1"
          height="200"
          width="200"
          @click="toggle"
        >
          <img
            src="https://img.freepik.com/vector-gratis/blogueando-divertido-creacion-contenido-streaming-online-videoblog-chica-joven-haciendo-selfie-red-social-compartir-comentarios-estrategia-autopromocion_335657-2386.jpg"
            alt="Imagen de vlog"
            style="max-width: 100%; max-height: 100%"
          />
          <div class="d-flex fill-height align-center justify-center">
            <v-scale-transition>
              <v-icon
                v-if="isSelected"
                color="white"
                icon="mdi-close-circle-outline"
                size="48"
              ></v-icon>
            </v-scale-transition>
          </div>
        </v-card>
      </v-slide-group-item>
    </v-slide-group>
  </v-sheet>
</template>

<script>
export default {
  data: () => ({
    model: [],
  }),
};
</script>
