<template>
  <v-container>
    <v-card class="card">
      <v-card-title class="card__title py-8">Cad</v-card-title>
      <v-card-text class="card__text" style="text-align:left;">
        Fusion360を用いてものつくりをしています。<br>
        最近代表はテオヤンセンと3Dプリンタにはまっています。</v-card-text>
      <v-row class="px-3">
        <v-col
          v-for="n in 3"
          :key="n"
          cols=4
        >
          <v-card>
            <v-img
              v-bind:src="'cad'+ n +'.png'"
              />
          </v-card>
        </v-col>
      </v-row>
      <div class="links">
        <nuxt-link class="button--grey" to="/">home</nuxt-link>
      </div>
    </v-card>
  </v-container>
</template>

<style>

</style>

