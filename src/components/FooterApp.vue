<template>
  <v-footer
    dark
    padless
  >
    <v-card
      flat
      tile
      class="indigo lighten-1 white--text text-center"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
      Ofrecemos un servicio personalizado de calidad y confiabilidad, a través de la buena atención de nuestro personal capacitado. Diseñamos viajes únicos a precios accesibles, logrando superar las expectativas de nuestros clientes.
       Somos FlyLG ¡Poniendo alas a tus sueños!
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>FLY LG</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>
<script>
export default {
    data() {
        return {
            icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
        }
    },
}
</script>
<style lang="">
    
</style>