<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/icon.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <v-card
          color="primary"
          class="mx-auto"
          prepend-icon="mdi-web-clock"
          subtitle="The #1 Vue UI Library"
          width="800"
        >
          <template v-slot:title>
            <span class="font-weight-black">
              Willkommen bei Kälte Klima Lüftungstechnik Führer
            </span>
          </template>
          <template v-slot:subtitle>
            <span class="font-weight-gray">
              Hier ensteht gerade unsere neue Webseite
            </span>
          </template>
          <v-card-text class="bg-surface-light pt-4">
            <v-container>
              <v-row align="center" justify="center" class="fill-height">
                <p class="font-weight-gray">
                  Gerne nehmen wir Ihre Anfragen jetzt schon entgegen!
                </p>
              </v-row>
              <v-row align="center" justify="center" class="fill-height">
                <p class="font-weight-gray">
                  Sie können uns unter folgenden Kontaktdaten erreichen:
                </p>
              </v-row>
              <v-row>
                <v-col>
                  <v-icon icon="mdi-email-edit-outline"></v-icon>
                </v-col>
                <v-col>
                  <span class="font-weight-gray">info@kkl-fuehrer.de</span>
                </v-col>
              </v-row>
              <v-row>
                <v-col>
                  <v-icon icon="mdi-cellphone"></v-icon>
                </v-col>
                <v-col>
                  <span class="font-weight-gray">+49 173 4364670</span>
                </v-col>
              </v-row>
            </v-container>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    ecosystem: [
      {
        text: "vuetify-loader",
        href: "https://github.com/vuetifyjs/vuetify-loader/tree/next",
      },
      {
        text: "github",
        href: "https://github.com/vuetifyjs/vuetify/tree/next",
      },
      {
        text: "awesome-vuetify",
        href: "https://github.com/vuetifyjs/awesome-vuetify",
      },
    ],
    importantLinks: [
      {
        text: "Chat",
        href: "https://community.vuetifyjs.com",
      },
      {
        text: "Made with Vuetify",
        href: "https://madewithvuejs.com/vuetify",
      },
      {
        text: "Twitter",
        href: "https://twitter.com/vuetifyjs",
      },
      {
        text: "Articles",
        href: "https://medium.com/vuetify",
      },
    ],
    whatsNext: [
      {
        text: "Explore components",
        href: "https://vuetifyjs.com",
      },
      {
        text: "Roadmap",
        href: "https://vuetifyjs.com/introduction/roadmap/",
      },
      {
        text: "Frequently Asked Questions",
        href: "https://vuetifyjs.com/getting-started/frequently-asked-questions",
      },
    ],
  }),
};
</script>
