<template>
  <v-footer
    dark
    height="auto"
  >
    <v-card
      flat
      tile
      width="100%"
      class="green lighten-1 white--text text-xs-center"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-3 white--text"
          icon
        >
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        Sanitec Aps <br>
        Mølleparken 47 <br>
        7184 Vandel <br>
        CVR 37828084 <br>
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        &copy; 2019 <strong>Sanitec Aps</strong> — All rights reserved
      </v-card-text>
    </v-card>
  </v-footer>
</template>


<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {

  },
})
export default class Footer extends Vue {

  constructor() {
    super();

  }

}
</script>