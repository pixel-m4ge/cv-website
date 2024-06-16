<template>
  <v-card class="rounded-0 h-100">
    <v-container class="py-0">
      <v-row>
        <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
        <v-col sm="8" cols="12">
          <v-tabs
            v-model="tab"
            align-tabs="center"
            bg-color="grey-darken-4"
            height="60"
            slider-color="honeydew"
            grow
          >
            <v-tab class="text-capitalize" value="tab-1">
              <template v-slot:prepend>
                <v-icon
                  icon="mdi-home"
                  :class="{ 'ml-3': $vuetify.display.xs }"
                ></v-icon>
              </template>
              <span class="d-none d-sm-block">Summary</span>
            </v-tab>

            <v-tab class="text-capitalize" value="tab-2">
              <template v-slot:prepend>
                <v-icon
                  icon="mdi-briefcase"
                  :class="{ 'ml-3': $vuetify.display.xs }"
                ></v-icon>
              </template>
              <span class="d-none d-sm-block">Experience</span>
            </v-tab>

            <v-tab class="text-capitalize" value="tab-3">
              <template v-slot:prepend>
                <v-icon
                  icon="mdi-medal"
                  :class="{ 'ml-3': $vuetify.display.xs }"
                ></v-icon>
              </template>
              <span class="d-none d-sm-block">Awards</span>
            </v-tab>

            <v-tab class="text-capitalize" value="tab-4">
              <template v-slot:prepend>
                <v-icon
                  icon="mdi-school"
                  :class="{ 'ml-3': $vuetify.display.xs }"
                ></v-icon>
              </template>
              <span class="d-none d-sm-block">Education</span>
            </v-tab>
          </v-tabs>
        </v-col>
        <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
      </v-row>
    </v-container>

    <v-tabs-window v-model="tab">
      <v-tabs-window-item key="1" value="tab-1">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
            <v-col sm="8" cols="12">
              <v-card variant="flat" class="bg-grey-darken-3" title="Zoe Curry">
                <template v-slot:subtitle>
                  <span class="text-body-1">Software Developer</span>
                </template>
                <v-card-text>
                  <span class="mr-4">
                    <a
                      href="https://www.linkedin.com/in/zoecurry/"
                      target="_blank"
                      rel="noopener noreferrer"
                      aria-label="Go to my LinkedIn profile"
                    >
                      <v-icon color="white" icon="mdi-linkedin"></v-icon>
                    </a>
                  </span>
                  <span>
                    <a
                      href="https://github.com/pixel-m4ge/"
                      target="_blank"
                      rel="noopener noreferrer"
                      aria-label="Go to my GitHub profile"
                    >
                      <v-icon color="white" icon="mdi-github"></v-icon>
                    </a>
                  </span>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div>
                    I have 4+ years of full-stack development experience,
                    specialising in front-end web development. My dissertation
                    focused on web accessibility, underlining my dedication to
                    inclusive web design.
                  </div>
                  <div class="pt-2">
                    I placed third in a competitive UK coding tournament,
                    demonstrating my proficiency in secure coding practices. I
                    utilise my creative background to inform and enhance my
                    development work.
                  </div>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-honeydew rounded">
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
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="2" value="tab-2">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
            <v-col sm="8" cols="12">
              <v-card
                variant="flat"
                class="bg-grey-darken-3"
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
                          class="text-white"
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
                  <div class="bg-honeydew rounded">
                    <div class="pa-4">
                      <div>Languages</div>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-code-tags"
                        >HTML</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-code-braces"
                        >CSS</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-language-javascript"
                        >JavaScript</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-code-parentheses"
                        >C#</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-database"
                        >SQL</v-chip
                      >
                    </div>
                  </div>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-honeydew rounded">
                    <div class="pa-4">
                      <div>Technologies</div>
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-vuejs"
                        >Vue</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-nuxt"
                        >Nuxt</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-vuetify"
                        >Vuetify</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-microsoft-azure-devops"
                        >Azure DevOps</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-github"
                        >GitHub</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-code-brackets"
                        >.NET</v-chip
                      >
                      <v-chip
                        variant="flat"
                        color="grey-darken-4"
                        label
                        class="mr-2 mt-2"
                        append-icon="mdi-cloud-braces"
                        >REST APIs</v-chip
                      >
                    </div>
                  </div>
                </v-card-text>
                <v-card-text class="pt-0">
                  <div class="bg-honeydew rounded">
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
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="3" value="tab-3">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
            <v-col sm="8" cols="12">
              <v-card variant="flat" class="bg-grey-darken-3" title="Awards">
                <v-card-text>
                  <v-expansion-panels
                    class="bg-honeydew"
                    variant="accordion"
                    flat
                    multiple
                  >
                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-security" />
                        <span class="pl-6 text-body-1">
                          4 Nations Secure Code Warrior Tournament
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">QA</div>
                        <div class="pt-2">
                          I competed against other participants in a series of
                          vulnerable code challenges, where I identified
                          problems, located weaknesses, and fixed
                          vulnerabilities.
                        </div>
                        <div class="pt-2">
                          In the knockout stage, I was one of the
                          highest-ranking competitors in Wales. I was then
                          invited to compete in the national final, where I
                          placed 3rd in the UK.
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-camera" />
                        <span class="pl-6 text-body-1">
                          Slim Hewitt Prize
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          University of Gloucestershire
                        </div>
                        <div class="pt-2">
                          The prize is awarded to the graduating Photojournalism
                          and Documentary Photography student achieving the
                          highest mark total for their level 6 modules.
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-camera-iris" />
                        <span class="pl-6 text-body-1">
                          Canon Student Development Programme
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          Visa Pour L'Image 2018
                        </div>
                        <div class="pt-2">
                          I attended workshops from acclaimed Canon Ambassadors
                          and industry experts, and networked with other
                          upcoming photographers.
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-hand-heart" />
                        <span class="pl-6 text-body-1">
                          Future Plan Volunteer of The Year
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          SU Student Awards 2018
                        </div>
                        <div class="pt-2">
                          I was nominated for this award by the Volunteer
                          Coordinator at The Cheltenham Trust, for my volunteer
                          work at The Wilson Art Gallery and Museum.
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-trophy-variant" />
                        <span class="pl-6 text-body-1">
                          Gold, Silver & Bronze Employability Award
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          University of Gloucestershire
                        </div>
                        <div class="pt-2">
                          The three levels require 100 hours of work experience,
                          4 employability workshops, 2 mock interviews, and a
                          formal presentation.
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>
                  </v-expansion-panels>
                </v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      <v-tabs-window-item key="4" value="tab-4">
        <v-container>
          <v-row>
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
            <v-col sm="8" cols="12">
              <v-card variant="flat" class="bg-grey-darken-3" title="Education">
                <v-card-text>
                  <v-expansion-panels
                    class="bg-honeydew"
                    variant="accordion"
                    flat
                    multiple
                  >
                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-school" />
                        <span class="pl-6 text-body-1">
                          BSc (Hons) Digital and Technology Solutions
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          University of South Wales
                        </div>
                        <div>2019 - 2024</div>
                        <div class="pt-2">
                          Predicted to graduate with a First Class
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-school" />
                        <span class="pl-6 text-body-1">
                          BA (Hons) Photojournalism and Documentary Photography
                        </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          University of Gloucestershire
                        </div>
                        <div>2016 - 2019</div>
                        <div class="pt-2">Graduated with a First Class</div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-certificate" />
                        <span class="pl-6 text-body-1"> A Levels </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          St David's Catholic College
                        </div>
                        <div>2014 - 2016</div>
                        <div class="pt-2">
                          Photography (B), Film Studies (A*), Business Studies
                          (B)
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>

                    <v-expansion-panel class="bg-honeydew">
                      <v-expansion-panel-title>
                        <v-icon icon="mdi-certificate" />
                        <span class="pl-6 text-body-1"> GCSEs </span>
                      </v-expansion-panel-title>
                      <v-expansion-panel-text>
                        <div class="font-weight-bold">
                          Bryn Hafren Comprehensive School
                        </div>
                        <div>2008 - 2013</div>
                        <div class="pt-2">
                          9 GCSEs Grade A-B including Maths and English (4 As, 5
                          Bs)
                        </div>
                      </v-expansion-panel-text>
                    </v-expansion-panel>
                  </v-expansion-panels>
                </v-card-text>
              </v-card>
            </v-col>
            <v-col sm="2" cols="0" class="d-none d-sm-block"></v-col>
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

<style>
.v-card-subtitle {
  opacity: 1 !important;
}
</style>
