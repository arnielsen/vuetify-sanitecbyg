<template>
  <v-footer
    dark
    height="auto"
  >

    <v-container fluid pa-0>
      <v-layout row wrap fill-height>
        <v-flex xs12 sm3 pa-5>
          <h2 class="headline text-uppercase mb-4">Sanitec Aps</h2>
          <div>Mølleparken 47</div>
          <div>7184 vandel</div>
          <div>CVR 37828084</div>
        </v-flex>
        <v-flex xs12 sm6 pa-5>
          <h2 class="headline text-uppercase mb-4">Samarbejdspartnere</h2>
          <ul>
            <li><a href="https://www.3dform.dk/" >Arkitektfirma 3D Form</a></li>
          </ul>
        </v-flex>
        <v-flex xs12>
          <div class="text-xs-center pt-4 pb-4">
            &copy; 2019 <strong>Sanitec Aps</strong> — All rights reserved
          </div>
          
        </v-flex>
      </v-layout>
    </v-container>

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