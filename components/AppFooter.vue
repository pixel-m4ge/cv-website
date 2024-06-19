<template>
  <v-footer class="pa-0">
    <v-row no-gutters>
      <v-col>
        <div class="px-4 py-2 w-100 bg-blueGray text-center">
          <span class="mx-4">
            <a
              href="https://www.linkedin.com/in/zoecurry/"
              target="_blank"
              rel="noopener noreferrer"
              aria-label="Go to my LinkedIn profile"
            >
              <v-icon color="black" icon="mdi-linkedin"></v-icon>
            </a>
          </span>
          <span class="mx-4">
            <a
              href="https://github.com/pixel-m4ge/"
              target="_blank"
              rel="noopener noreferrer"
              aria-label="Go to my GitHub profile"
            >
              <v-icon color="black" icon="mdi-github"></v-icon>
            </a>
          </span>
          <span class="mx-4">
            <a
              href="mailto:zoe@pixelmage.dev"
              target="_blank"
              rel="noopener noreferrer"
              aria-label="Email me"
            >
              <v-icon color="black" icon="mdi-email"></v-icon>
            </a>
          </span>
        </div>
        <div class="px-4 py-2 w-100 bg-grey-darken-4 text-center">
          &copy; Zoe Curry — {{ new Date().getFullYear() }}
        </div>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script>
export default {
  data: () => ({}),
};
</script>

<style>
a {
  display: inline-block;
}
</style>
