<template>
  <v-app>
    <v-app-bar color="#BF8BAB" fixed app>
      <v-toolbar-title v-text="title" />
      <v-spacer />
    </v-app-bar>
    <v-main>
      <nuxt />
    </v-main>
    <v-footer app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: 'Bäckerei Heusser',
    }
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;700;800&display=swap');

:root {
  --black: #260c11;
  --white: #f2f2f2;
  --primary: #9e3e6e;
  --secondary: #bf8bab;
  --yellow: #f2c020;
  --orange: #f2a922;
  --brown: #bf6e0b;
}

body {
  margin: 0;
  font-family: 'Inter', 'Helvetica Neue', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

code {
  font-family: source-code-pro, Menlo, Monaco, Consolas, 'Courier New',
    monospace;
}

.v-app-bar {
  border-bottom: 5px solid var(--primary) !important;
}

.theme--dark.v-application {
  background: var(--secondary);
}
</style>
