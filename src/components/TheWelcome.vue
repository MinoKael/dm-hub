<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/">
      <v-btn> Home </v-btn>
    </RouterLink>
    <RouterLink to="/dice">
      <v-btn> Dice </v-btn>
    </RouterLink>
    <RouterLink to="/magias">
      <v-btn> Magias </v-btn>
    </RouterLink>
  </nav>
</template>
