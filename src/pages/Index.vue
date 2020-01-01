<template>
  <Layout>

    <v-container fluid>
      <v-row>
        <v-col 
          cols="12"
          class="pa-12"
        >
          <!-- Learn how to use images here: https://gridsome.org/docs/images -->
          <g-image alt="Example image" src="~/favicon.png" width="135" />
          <h1>Gridsome Vuetify Starter</h1>
          <p>
            A quick starter template for my fellow non-designers
          </p>
          <p class="home-links">
            <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
            <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
          </p>
        </v-col>
      </v-row>

    </v-container>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Gridsome Vuetify Starter Template'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
