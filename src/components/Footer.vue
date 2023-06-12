<template>
  <v-footer dark padless>
    <v-card flat tile class="secondary white--text text-center">
      <v-card-text>
        <v-btn
          v-for="(icon, i) in icons"
          :key="i"
          class="mx-4 white--text"
          :href="icon.link"
          target="_blank"
          icon
        >
          <v-icon size="24px">{{ icon.text }}</v-icon>
        </v-btn>
      </v-card-text>
      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>Ahlida Sabila Larasati</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<style scoped>
.v-card {
  width: 100%;
}
</style>

<script>
export default {
  data: () => ({
    icons: [
    {
        text: "mdi-email",
        link: "https://sabilaahlida@gmail.com",
      },
      {
        text: "mdi-whatsapp",
        link: "https://wa.me/+6285726571307",
      },
      {
        text: "mdi-github",
        link: "https://github.com/ahlidasabila",
      },
      {
        text: "mdi-instagram",
        link: "https://instagram.com/ahlidasblra/",
      },
    ],
  }),
};
</script>
