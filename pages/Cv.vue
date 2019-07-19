<template>
    <div style="display:flex; justify-content:center; flex-direction:column; align-items:center;">
        <h2>MY Curriculum Vitae</h2>
         <v-container fluid grid-list-md>
             <v-flex d-flex xs12 sm6 md12>
                <v-card color="green lighten-2" dark>
                <v-card-title primary class="title">Presentation</v-card-title>
                <v-card-text>{{ presentation }}</v-card-text>
                </v-card>
            </v-flex>
            <v-layout row wrap>
                    <v-flex d-flex xs12 sm4 md8>
                        <v-card color="indigo lighten-1" dark>
                        <v-card-title primary class="title">Expériences</v-card-title>
                        <v-card-text>{{ lorem }}</v-card-text>
                        </v-card>
                    </v-flex>
                     <v-flex d-flex>
                    <v-card color="red lighten-2" dark>
                    <v-card-title primary class="title">Compétences</v-card-title>
                    </v-card>
                </v-flex>
                    <v-flex d-flex xs12 sm6 md8>
                        <v-card color="indigo lighten-1" dark>
                        <v-card-title primary class="title">Formation</v-card-title>
                        <v-card-text>{{ lorem }}</v-card-text>
                        </v-card>
                    </v-flex>
                    <v-flex d-flex xs12 sm12 md4>
            <v-layout row wrap>
                <v-flex d-flex>
                    <v-card color="red lighten-2" dark>
                    <v-card-title>cms</v-card-title>
                    <v-card-text>{{ lorem }}</v-card-text>
                </v-card>
                </v-flex>
                <v-flex d-flex>
                    <v-card color="red lighten-2" dark>
                    <v-card-title>frameworks</v-card-title>
                    <v-card-text>{{ lorem }}</v-card-text>
                </v-card>
                </v-flex>
                <v-flex d-flex>
            <v-layout row wrap>
                <v-flex d-flex xs12>
                        <v-card
                        color="red lighten-2"
                        dark
                        >
                        <v-card-text>langage de programmation</v-card-text>
                          <v-card-text>{{ lorem }}</v-card-text>
                        </v-card>
                    </v-flex>
                </v-layout>
                </v-flex>
            </v-layout>
            </v-flex>
            <!-- <v-flex d-flex xs12 sm6 md2 child-flex>
                <v-card color="green lighten-2" dark>
                <v-card-text>{{ lorem.slice(0, 90) }}</v-card-text>
                </v-card>
            </v-flex> -->
            </v-layout>
        </v-container>
    </div>
</template>

<script>
  export default {
    data: () => ({
      presentation : `Afin d'élargir mes compétences, je souhaite poursuivre ma deuxième année dans une entreprise de services numériques (ESN).
      Mon objectif est de maîtriser l’architecture client/serveur dans le but de devenir un développeur web confirmé.
        Je suis capable de concevoir des interfaces Web en JavaScript avec les Framework ANGULAR & VUEJS.
    Coté backend, je peux créer des web services/api avec NodeJS pour servir le front.
    De plus, je peux travailler sur des projets en PHP notamment sur Laravel ou Symfony.
    Le rythme d'alternance en contrat de professionnalisation : 1 semaine en cours et 3 semaines en entreprise.`,
      lorem: `Lorem ipsum dolor sit amet, mel at clita quando. Te sit oratio vituperatoribus, nam ad ipsum posidonium mediocritatem, explicari dissentiunt cu mea. Repudiare disputationi vim in, mollis iriure nec cu, alienum argumentum ius ad. Pri eu justo aeque torquatos.`
    })
  }
</script>
