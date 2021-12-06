<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
      class="indigo lighten-1"
    >
      <v-list>
        <v-list-item
          v-for="link in links"
          :key="link"
          :to="link.path"
          style="color:white"
        >
        {{ link.text }}
        </v-list-item>
      </v-list>

    </v-navigation-drawer>

    <v-app-bar app class="indigo lighten-1 white--text text-center">
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      
      <v-toolbar-title>PRUR</v-toolbar-title>
      
    </v-app-bar>

    <v-main>
      <router-view></router-view>

       <v-footer
    dark
    padless
  >
    <v-card
      class="flex"
      flat
      tile
    >
      <v-card-title class="indigo lighten-1 white--text text-center">
        <strong class="subheading">Prondađite nas na društvenim mrežama!</strong>

        <v-spacer></v-spacer>

        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          dark
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-title>

      <v-card-text class="py-2 white--text text-center">
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-card-text>
    </v-card>
  </v-footer>


    </v-main>
  </v-app>
</template>


<script>
  export default {
    data: () => ({ 
      drawer: null,
       links: [
        {
          text: 'Naslovnica',
          path: '/'
        },
        {
          text: 'O nama',
          path: '/About'
        },
       ],
       icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],

      }),
  }
</script>