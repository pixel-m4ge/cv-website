<template>
  <v-card class="rounded-0 h-100">
    <v-tabs v-model="tab" align-tabs="center" bg-color="indigo">
      <v-tab prepend-icon="mdi-home" value="tab-1">Summary</v-tab>

      <v-tab prepend-icon="mdi-briefcase" value="tab-2">Experience</v-tab>

      <v-tab prepend-icon="mdi-medal" value="tab-3">Awards</v-tab>

      <v-tab prepend-icon="mdi-school" value="tab-4">Education</v-tab>
    </v-tabs>

    <v-tabs-window v-model="tab">
      <v-tabs-window-item key="1" value="tab-1">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0"></v-col>
            <v-col sm="8" cols="12">
              <v-card
                variant="flat"
                class="bg-indigo-lighten-5"
                title="Summary"
              >
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="2" value="tab-2">
        <v-container>
          <v-row>
            <v-col cols="2"></v-col>
            <v-col cols="8">
              <v-card
                variant="flat"
                class="bg-indigo-lighten-5"
                title="Experience"
              >
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col cols="2"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="3" value="tab-3">
        <v-container>
          <v-row>
            <v-col cols="2"></v-col>
            <v-col cols="8">
              <v-card variant="flat" class="bg-indigo-lighten-5" title="Awards">
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col cols="2"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="4" value="tab-4">
        <v-container>
          <v-row>
            <v-col cols="2"></v-col>
            <v-col cols="8">
              <v-card
                variant="flat"
                class="bg-indigo-lighten-5"
                title="Education"
              >
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col cols="2"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
    </v-tabs-window>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      tab: null,
    };
  },
};
</script>
