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
                <v-card-text>
                  <div class="text-body-1">Welsh Revenue Authority</div>
                  <div class="font-weight-bold">Sep 2019 - Present</div>
                  <div class="pl-4 pt-2">
                    <ul>
                      <li>
                        Build and support software for both internal and
                        external users
                      </li>
                      <li>
                        Front-end JavaScript applications and back-end .NET API
                        services
                      </li>
                      <li>
                        Support and mentor apprentice developers in enhancing
                        their skills
                      </li>
                      <li>
                        Work within Agile service teams to deliver
                        customer-centric applications
                      </li>
                      <li>
                        Effectively elevate applications to achieve the highest
                        level of WCAG
                      </li>
                      <li>
                        Nominated as
                        <a
                          href="https://www.gov.wales/welsh-revenue-authority/zoe-curry"
                          target="_blank"
                          rel="noopener noreferrer"
                          aria-label="Go to my Staff Elected Member profile"
                          >Staff Elected Member
                        </a>
                        for the WRA board
                      </li>
                    </ul>
                  </div>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-indigo-lighten-4" style="border-radius: 4px">
                    <div class="pa-4">
                      <div>Languages</div>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >HTML</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >CSS</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >JavaScript</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >C#</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >SQL</v-chip
                      >
                    </div>
                  </div>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-indigo-lighten-4" style="border-radius: 4px">
                    <div class="pa-4">
                      <div>Technologies</div>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >Vue</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >Nuxt</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >Vuetify</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >Azure DevOps</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >GitHub</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >.NET</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        >REST APIs</v-chip
                      >
                    </div>
                  </div>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-indigo-lighten-4" style="border-radius: 4px">
                    <div class="pa-4">
                      <div>Certifications</div>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-open-in-new"
                      >
                        <a
                          class="text-white"
                          href="https://learn.microsoft.com/en-us/users/zoecurry-6255/credentials/964d029176c11da0"
                          target="_blank"
                          rel="noopener noreferrer"
                          aria-label="Go to my Microsoft Azure Fundamentals certificate"
                        >
                          Microsoft Azure Fundamentals
                        </a>
                      </v-chip>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-open-in-new"
                      >
                        <a
                          class="text-white"
                          href="https://www.icagile.com/credentials/7a32b554-d9fd-48ea-87c1-20f291b5c187"
                          target="_blank"
                          rel="noopener noreferrer"
                          aria-label="Go to my ICAgile Certified Professional certificate"
                        >
                          ICAgile Certified Professional
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
