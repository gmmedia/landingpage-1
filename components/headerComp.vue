<template>
  <v-app-bar app min-height="64px" class="white">
    <v-app-bar-nav-icon @click="drawer = true" class="hidden-md-and-up"></v-app-bar-nav-icon>
    <v-toolbar-title>Elegant Themes Divi - Das beste WordPress Theme</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn text v-for="link in links" :key="link.title" :to="link.href">
        {{ link.title }}
      </v-btn>
      <v-btn color="primary" href="https://j0e.org/tipp/Divi" rel="nofollow noopener" target="_blank">
        Hole dir DIVI
      </v-btn>
    </v-toolbar-items>
    
    <v-navigation-drawer left app v-model="drawer" absolute temporary class="hidden-md-and-up">
      <v-list nav dense>
        <v-list-item-group active-class="deep-purple--text text--accent-4">
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-home</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-account</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Account</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
  </v-app-bar>
</template>

<script>
export default {
  data () {
    return {
      links: [
        { title: 'Home', href: '/' },
        { title: 'About Us', href: '/about' },
        { title: 'Impressum', href: 'https://j0e.org/impressum/' },
      ],
      icons: [
        { title: 'mdi-facebook', href: 'https://www.facebook.com/j0e.org' },
        { title: 'mdi-twitter', href: 'https://twitter.com/j0e_org' },
        { title: 'mdi-instagram', href: 'https://www.instagram.com/j0eorg/' },
      ],
      drawer: false,
    }
  },
  methods: {
    menuItems() {
      return this.menu;
    }
  }
}
</script>

<style>
.theme--light.v-btn--active::before {
  opacity: 0;
}
</style>