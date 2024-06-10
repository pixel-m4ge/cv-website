<template>
  <v-footer class="pa-0">
    <v-row no-gutters>
      <v-col>
        <div class="px-4 py-2 w-100 bg-indigo text-center">
          <a
            href="https://www.linkedin.com/in/zoecurry/"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Go to my LinkedIn profile"
          >
            <v-icon color="white" icon="mdi-linkedin" class="mx-4"></v-icon>
          </a>
          <a
            href="https://github.com/pixel-m4ge/"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Go to my GitHub profile"
          >
            <v-icon color="white" icon="mdi-github" class="mx-4"></v-icon>
          </a>
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
