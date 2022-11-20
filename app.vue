<template>
  <v-app>
    <v-app-bar>
      <v-row justify="space-around">
        <v-icon
          size="large"
          color="green-darken-2"
        >
          mdi-domain
        </v-icon>

        <v-icon
          size="large"
          color="blue-darken-2"
        >
          mdi-message-text
        </v-icon>

        <v-icon
          size="large"
          color="purple-darken-2"
        >
          mdi-dialpad
        </v-icon>

        <v-icon
          size="large"
          color="teal-darken-2"
        >
          mdi-email
        </v-icon>

        <v-icon
          size="large"
          color="blue-grey-darken-2"
        >
          mdi-call-split
        </v-icon>

        <v-icon
          size="large"
          color="orange-darken-2"
        >
          mdi-arrow-up-bold-box-outline
        </v-icon>
      </v-row>
    </v-app-bar>

    <v-navigation-drawer penent>
      Navigation Drawer
    </v-navigation-drawer>

    <v-main>
      <v-container>
        Main Contents
      </v-container>
    </v-main>

    <v-bottom-navigation>
      Button Navigation
    </v-bottom-navigation>

    <v-footer>
      Footer
    </v-footer>

  </v-app>
</template>