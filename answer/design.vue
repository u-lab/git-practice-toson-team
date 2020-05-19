<template>
<div>
  <div>
  <v-app  style="background-color:rgba(0,0,0,0);">
    <v-container>
      <v-card class="card">
        <v-card-title class="card__title py-8">Design</v-card-title>
        <v-card-text class="card__text" style="text-align:left;">Processingを用いたGenerativeArt、Webデザイン等を行っています。</v-card-text>
        <v-row class="px-3">
          <v-col
            v-for="n in 3"
            :key="n"
            cols=4
          >
            <v-card>
              <v-img
                v-bind:src="'design'+ n +'.png'"
                />
            </v-card>
          </v-col>
        </v-row>
        <div class="links">
          <nuxt-link class="button--grey" to="/">home</nuxt-link>
        </div>
      </v-card>
    </v-container>
  </v-app>
  </div>
</div>
</template>

<style>
  
</style>

