<template>
  <div class="d-flex flex-column flex-md-row justify-md-center align-center pa-6 pa-sm-16 pa-md-16">
    <div class="container-virtual">
      <div class="virtual-image"></div>
    </div>

    <v-container>
      <v-row class="d-flex flex-column pa-md-5 w-xl-75">
        <v-col class="pa-0 pa-md-5 pa-lg-5" cols="12" sm="12" md="10">
          <p class="text-uppercase font-weight-bold mb-5 mt-sm-5 virtual-subtitle">technology</p>
          <h3 class="text-h3 text-md-h2 mb-5 virtual-title">Virtual Reality</h3>
          <p class="virtual-description">
            There are only some symptoms such as dizziness, depression, and collapse that appear
            while the VR experience. The technology is still new and requires investigation and
            research.
          </p>
          <v-divider :thickness="1" class="border-opacity-100 mt-5 mt-md-5 mb-5 mb-md-5 virtual-divider"></v-divider>
        </v-col>

        <v-col class="d-flex align-center pa-0 pa-md-5 pa-lg-0 pa-lg-5" cols="12" sm="12" md="10">
          <v-avatar size="60" class="mr-3 mr-md-5 mt-5 mt-md-0">
            <v-icon class="mdi mdi-lightbulb-on-10 virtual-icon" size="20"></v-icon>
          </v-avatar>
          <p class="virtual-description mt-5 mt-md-0">
            Sample text. Click to select the text box. Click again or double click to start editing
            the text. Duis aute irure dolor.
          </p>
        </v-col>

        <v-col class="d-flex align-center pa-0 pa-md-5 pa-lg-5" cols="12" sm="12" md="10">
          <v-avatar size="60" class="mr-3 mr-md-5 mt-5 mt-md-0">
            <v-icon class="mdi mdi-wifi virtual-icon" size="20"></v-icon>
          </v-avatar>
          <p class="virtual-description mt-5 mt-md-0">
            Sample text. Click to select the text box. Click again or double click to start editing
            the text. Duis aute irure dolor.
          </p>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<style></style>
