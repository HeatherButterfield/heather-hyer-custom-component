<template>
  <v-container class="d-flex justify-space-around">
    <v-card
      max-width="344"
      class="mx-auto"
      v-for="index in 5"
      v-bind:key="index"
    >
      <v-card-title>Server #{{ index }}</v-card-title>
    </v-card>
  </v-container>
</template>

<script>
</script>

<style>

</style>
