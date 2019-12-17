<template>
  <v-app>
    <div>
      <v-app-bar>
        <v-btn
          icon
          :to="$url('/')"
          title="Home"
        >
          <v-icon>home</v-icon>
        </v-btn>
        <v-toolbar-title>{{ $static.metadata.siteName }}</v-toolbar-title>
        <v-spacer />

        <v-btn text :to="$url('/')">
          Home
        </v-btn>
        <v-btn text :to="$url('/about')">
          About
        </v-btn>
      </v-app-bar>
    </div>
    <v-container>
      <slot />
    </v-container>
  </v-app>
</template>

<static-query>
  query {
    metadata {
      siteName
    }
  }
</static-query>

<style>

</style>
