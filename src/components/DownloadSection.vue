<template>
  <section id="download">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col sm="4" class="hidden-xs-only">
              <v-img src="@/assets/img/ill2.svg" class="d-block ml-auto mr-auto" max-width="350px" />
            </v-col>
            <v-col cols="12" sm="8" class="white--text text-left">
              <h1 class="font-weight-light display-2 mb-2">About Project</h1>
              <h1 class="font-weight-light">
                Hello Everyone, Lets get acquainted and see further about the field 
                that I'm interested in through my portfolio below.
              </h1>
              <v-btn rounded outlined href="https://drive.google.com/drive/folders/1NJo122Cf9ho0GdXv38F7T6qin94B4VR8?usp=sharing" target="_blank" large color="white" class="mt-4">
                <v-icon class="mr-2">
                  mdi-google-drive
                </v-icon>
                Google Drive
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#download {
  background-image: url("~@/assets/img/bgDownload.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 500px;
}

#download .container,
#download .row {
  height: 100%;
}
</style>