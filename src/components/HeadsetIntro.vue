<template>
  <div class="d-flex flex-column flex-sm-row flex-md-row mt-8 mt-md-0">
    <v-container class="d-flex pa-0 justify-center" fluid>
      <v-row no-gutters>
        <v-col class="d-flex align-center justify-md-end" cols="12" md="12">
          <div class="vr-headsets-info pl-12">
            <v-divider :thickness="6" class="divider-info border-opacity-100 w-25"></v-divider>
            <h1 class="text-h3 text-sm-h4 text-md-h3 mb-6 mt-6 mb-sm-6 title-info">VR headsets</h1>
            <p class="mb-6 descrip-vr pr-12 font-weight-bold">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
              nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
            <v-btn
              class="read-more-btn text-h6 text-md-5 text-uppercase mb-6"
              height="66"
              width="300"
              variant="outlined"
            >
              Read More
            </v-btn>
          </div>
        </v-col>
      </v-row>
    </v-container>

    <div class="d-flex justify-end justify-md-center image-container mt-4">
      <img src="../assets/images/esff.jpg" alt="VR Headsets" class="image-vr-head" />
    </div>
  </div>
</template>
