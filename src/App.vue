<template>
  <v-app>
    <nav class="text-center">
      <router-link :to="{ name: 'HomeView' }">Home</router-link> |
      <router-link :to="{ name: 'AboutView' }">About</router-link>
    </nav>
    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script setup lang="ts"></script>
