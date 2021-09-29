<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="10" lg="10">
      <v-card class="logo py-4 d-flex justify-center">
        <h2>Data Set Collector</h2>
      </v-card>
      <v-card>
        <v-card-title class="headline">
          Welcome to the Data Set collector project
        </v-card-title>
        <v-card-text>
          <v-row style="height: 100%">
            <v-col>
              <v-textarea label="Source text" height="auto"></v-textarea>
              </v-col>
            <v-col>
              <v-textarea label="Target text" height="auto"></v-textarea>
            </v-col>
          </v-row>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
