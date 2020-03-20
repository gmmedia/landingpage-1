<template>
  <v-footer padless class="mt-12">
    <v-container>
      <v-row justify="center">
        <v-col cols="xl-7">
          <v-row justify="start" align="center">
          <p class="pr-5 pl-3">Folge uns</p>
          <p>
            <v-btn v-for="icon in icons" :key="icon.title" icon :href="icon.href" target="_blank">
              <v-icon size="24px">{{ icon.title }}</v-icon>
            </v-btn></p>
          </v-row>
        </v-col>
      </v-row>
      <v-row justify="center" no-gutters>
        <v-col cols="xl-6" class="text-center">
          <v-row justify="space-between">
            <v-btn
              v-for="link in links"
              :key="link.title"
              text
              class="my-2"
              :href="link.href"
            >
              {{ link.title }}
            </v-btn>
          </v-row>
        </v-col>
      </v-row>
        <v-divider></v-divider>
      <v-row>
        <v-col
          class="text-center"
          cols="12"
        >
          {{ new Date().getFullYear() }} — <strong>Jochen Gererstorfer</strong>
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
</template>

<script>
export default {
  data () {
    return {
      links: [
        { title: 'Home', href: '/' },
        { title: 'About Us', href: '/about' },
        { title: 'Impressum', href: 'https://j0e.org/impressum/' },
        { title: 'Datenschutz', href: 'https://j0e.org/datenschutz/' },
        { title: 'Kontakt', href: 'https://j0e.org/ueber-j0e-org/#kontakt' },
      ],
      icons: [
        { title: 'mdi-facebook', href: 'https://www.facebook.com/j0e.org' },
        { title: 'mdi-twitter', href: 'https://twitter.com/j0e_org' },
        { title: 'mdi-instagram', href: 'https://www.instagram.com/j0eorg/' },
      ],
    }
  },
}
</script>

<style>
</style>