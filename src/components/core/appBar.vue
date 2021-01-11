<template>
  <v-app-bar app color="white" height="75">
    <v-spacer></v-spacer>

    <div class="d-flex align-center">
      <v-img
        alt="Vuetify Logo"
        class="shrink mr-2"
        contain
        src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
        transition="scale-transition"
        width="40"
      />

      <v-img
        alt="Vuetify Name"
        class="shrink mt-1 hidden-sm-and-down"
        contain
        min-width="100"
        src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
        width="100"
      />
    </div>

    <v-text-field
      solo
      style="margin-top: 30px"
      height="45"
      label="search whatever you want to buy.."
      prepend-inner-icon="search"
    ></v-text-field>


    <v-btn height="50" style="margin-left: 15px;">
      <span class="mr-2">My Account</span>
      <v-icon>account_circle</v-icon>
    </v-btn>

    <v-btn height="50" style="margin-left: 15px; margin-right: 75px;">
      <span class="mr-2">Cart</span>
      <v-icon>shopping_cart</v-icon>
    </v-btn>
    <v-spacer></v-spacer>

  </v-app-bar>
</template>

<script>
export default {};
</script>

<style>
</style>