<template>
  <nav>
    <v-toolbar 
        app 
        fixed 
        flat 
        dark>
    <v-toolbar-title class="headline">
        <span>Sanitec</span>&nbsp;
        <span class="font-weight-light">ApS</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn v-for="link in links" :key="link.text" flat router :to="link.route">
        {{ link.text }}
      </v-btn>
    </v-toolbar-items>
    </v-toolbar>
  </nav>
</template>


<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {

  },
})
export default class NavBar extends Vue {
  links: any[];

  constructor() {
    super();

    this.links = [
            { text: 'Hjem', route: '/' },
            { text: 'Services', route: '/services' },
            { text: 'Referencer', route: '/references' },
            { text: 'Om os', route: '/about' },
            { text: 'Kontakt', route: '/contact' },
        ];
  }

}
</script>