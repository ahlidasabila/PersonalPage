<template>
  <section id="about">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col cols="12" md="7">
              <h1 class="font-weight-light display-2">MY Soft Skill</h1>
              <v-row>
                <v-col cols="12" class="d-flex align-center">
                  <v-img
                    src="@/assets/img/icon3.svg"
                    max-width="60px"
                    class="mr-4"
                  />
                  <p class="text-justify">
                    <br><br>
                    In daily life, I am also active in socializing with friends and the surrounding environment, 
                    I also often participate in activities that can support the development of my soft skills. 
                    As a result, based on submissions from my environment, I am a person who can communicate well, 
                    have a work ethic that can be developed as a team or individually. Likewise in solving problems, 
                    I tend to be able to solve problems around or that are being faced. 
                    This is certainly not easy if not with good time management, 
                    so that I also have the ability to rank my priorities in order to support my work productivity later.
                  </p>
                </v-col>
              </v-row>
            </v-col>
            <v-col cols="12" md="5" class="d-none d-md-flex">
              <v-img
                src="@/assets/img/ill1.svg"
                class="d-block ml-auto mr-auto"
                max-width="400px"
              />
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#about {
  background-color: #f4f7f5;
}
</style>
