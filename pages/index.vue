<template>
  <v-card class="rounded-0 h-100">
    <v-tabs v-model="tab" align-tabs="center" bg-color="indigo">
      <v-tab class="text-capitalize" prepend-icon="mdi-home" value="tab-1"
        >Summary</v-tab
      >

      <v-tab class="text-capitalize" prepend-icon="mdi-briefcase" value="tab-2"
        >Experience</v-tab
      >

      <v-tab class="text-capitalize" prepend-icon="mdi-medal" value="tab-3"
        >Awards</v-tab
      >

      <v-tab class="text-capitalize" prepend-icon="mdi-school" value="tab-4"
        >Education</v-tab
      >
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
                title="Zoe Curry"
              >
                <template v-slot:subtitle>
                  <span class="text-body-1">Software Developer</span>
                </template>
                <v-card-text>
                  I have 4+ years of full-stack development experience,
                  specialising in front-end web development. My dissertation
                  focused on web accessibility, underlining my dedication to
                  inclusive web design. I placed third in a competitive UK
                  coding tournament, demonstrating my proficiency in secure
                  coding practices. I utilise my creative background to inform
                  and enhance my development work.
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-indigo-lighten-4" style="border-radius: 4px">
                    <div class="pa-4">
                      <div>Projects</div>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-open-in-new"
                      >
                        <a
                          class="text-white"
                          href="https://github.com/pixel-m4ge"
                          target="_blank"
                          rel="noopener noreferrer"
                          aria-label="Go to my CV Website repository"
                        >
                          CV Website
                        </a>
                      </v-chip>
                    </div>
                  </div>
                </v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="2" value="tab-2">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0"></v-col>
            <v-col sm="8" cols="12">
              <v-card
                variant="flat"
                class="bg-indigo-lighten-5"
                title="Experience"
              >
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="3" value="tab-3">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0"></v-col>
            <v-col sm="8" cols="12">
              <v-card variant="flat" class="bg-indigo-lighten-5" title="Awards">
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="4" value="tab-4">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0"></v-col>
            <v-col sm="8" cols="12">
              <v-card
                variant="flat"
                class="bg-indigo-lighten-5"
                title="Education"
              >
                <v-card-text>...</v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0"></v-col>
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
