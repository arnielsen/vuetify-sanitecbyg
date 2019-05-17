<template>
 
 <v-content pt-5>
    <v-container fill-height="true">
      <v-layout justify-center align-center wrap="true">
        <v-flex xs12 mb-5>
          <v-container grid-list-x1 pa-0>
            
          <v-form name="contact" method="POST" data-netlify="true">
            <v-container>
              <v-layout row wrap>

                <v-flex xs12>
                  <v-text-field
                    v-model="name"
                    :rules="nameRules"
                    label="Navn"
                  ></v-text-field>
                </v-flex>
                <v-flex xs12>
                  <v-text-field
                    v-model="email"
                    :rules="emailRules"
                    label="E-mail"
                  ></v-text-field>
                </v-flex>
                <v-flex xs12>
                  <v-textarea
                    v-model="message"
                    :rules="messageRules"
                    label="Message"
                    
                  ></v-textarea>
                </v-flex>

                <input type="submit" class="v-btn v-btn-large success" />

              </v-layout>
            </v-container>
          </v-form>

          </v-container>
        </v-flex>
      </v-layout>
    </v-container>
  </v-content>

</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {
    
  },
})
export default class Contact extends Vue {}
</script>
