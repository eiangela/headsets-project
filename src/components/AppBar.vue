<template>
  <v-app-bar :elevation="0">
    <v-container>
      <v-row>
        <v-col class="d-flex justify-center align-center">
          <img
            src="../assets/images/logo.png"
            class="logo-image"
            width="auto"
            height="36"
            alt="Imagem do Logo"
          />
        </v-col>
        <v-col class="d-flex justify-center">
          <v-app-bar-nav-icon
            size="x-large"
            class="nav-icon-right"
            :ripple="false"
          ></v-app-bar-nav-icon>
        </v-col>
      </v-row>
    </v-container>
  </v-app-bar>
</template>
