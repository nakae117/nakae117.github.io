<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <v-app id="reports-app">
    <v-app-bar color="primary" elevation="2">
      <v-app-bar-title>Site App</v-app-bar-title>

      <v-btn href="/reports-app" icon>
        <v-icon>assignment</v-icon>
      </v-btn>
    </v-app-bar>

		<v-main class="bg-grey-lighten-3">
      <v-container class="mt-5">
        <RouterView />
      </v-container>
		</v-main>
	</v-app>
</template>