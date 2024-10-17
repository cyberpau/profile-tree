<template>
  <v-app-bar class="px-3" density="compact" flat>

    <!-- Left Spacer -->
    <v-spacer></v-spacer>

    <!-- Main Navigation Menu -->
    <v-tabs color="grey-darken-2" centered>
      <v-tab v-for="link in links" :key="link" :text="link"></v-tab>
    </v-tabs>

    <!-- Right Spacer -->
    <v-spacer></v-spacer>

  </v-app-bar>
</template>

<script setup>
const links = ["Dashboard", "Messages", "Profile", "Updates"];
</script>
