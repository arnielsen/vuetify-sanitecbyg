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
      <v-btn flat href="/">Hjem</v-btn>
      <v-btn flat href="/services">Services</v-btn>
      <v-btn flat href="/references">Referencer</v-btn>
      <v-btn flat href="/about">Om os</v-btn>
      <v-btn flat href="/contact">Kontakt</v-btn>
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

  constructor() {
    super();

  }

}
</script>