<template>
  <div class="container-surprising text-center pa-10 pa-md-16">
    <div>
      <h2 class="text-h3 text-md-h2 mb-5 surprising-title">VR's Surprising Benefits</h2>
      <p class="text-md-h6 surprising-descrip">
        Sample text. Click to select the text box. Click again or double click to start editing the
        text.
      </p>
    </div>
  </div>

  <v-container max-width="1280">
    <v-row>
      <v-col v-for="(benefit, i) in benefits" :key="i" cols="12" sm="6" md="4">
        <v-card class="text-center pa-4 rounded-lg">
          <v-avatar size="80">
            <v-icon size="50" class="benefit-icon">{{ benefit.icon }}</v-icon>
          </v-avatar>
          <v-card-title class="text-uppercase mb-5 mt-5 benefit-title font-weight-bold">
            {{ benefit.title }}
          </v-card-title>
          <v-card-text class="mb-5 benefit-descrip"> {{ benefit.description }}</v-card-text>
          <v-card-actions class="d--flex justify-center">
            <v-btn class="benefit-btn text-lowercase font-weight-bold" variant="outlined">
              More
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
const benefits = [
  {
    title: 'Mental Health',
    description:
      'Sample text. Click to select the text box. Click again or double click to start editing the text. Excepteur sint occaecat cupidatat non proident.',
    icon: 'mdi-safety-goggles'
  },
  {
    title: 'Realistic Experience',
    description:
      'Sample text. Click to select the text box. Click again or double click to start editing the text. Excepteur sint occaecat cupidatat non proident.',
    icon: 'mdi-virtual-reality'
  },
  {
    title: 'Relax',
    description:
      'Sample text. Click to select the text box. Click again or double click to start editing the text. Excepteur sint occaecat cupidatat non proident.',
    icon: 'mdi-radio-tower'
  }
]
</script>
