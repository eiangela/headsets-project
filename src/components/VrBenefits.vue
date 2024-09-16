<template>
  <v-container>
    <v-row>
      <v-col cols="12">
        <h4 class="text-center mb-4 text-h4 text-md-h3 vr-title">VR's Surprising Benefits</h4>
        <p class="text-center text-h6 text-md-h6 mt-md-8 vr-descrption">
          Sample text. Click to select the text box. Click again or double click to start editing
          the text.
        </p>
      </v-col>

      <v-col cols="12" sm="12" md="12">
        <v-card
          class="mt-4 d-flex align-md-center pa-3"
          v-for="(item, i) in vrBenefits"
          :key="i"
          :class="{ 'card-purple': item.number === '3' }"
        >
          <v-card-title
            class="text-md-h1 vr-item-number"
            :class="{ 'text-white-3': item.number === '3' }"
          >
            {{ item.number }}
          </v-card-title>
          <v-card-text
            class="pt-4 vr-card-description"
            :class="{ 'text-white-3': item.number === '3' }"
          >
            {{ item.text }}
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
const vrBenefits = [
  {
    number: '1',
    text: 'To reap the benefits of virtual reality in education, it is important for students to use VR equipment safely. VR users often spin around or stride blindly, ignoring their physical surroundings. A misstep could lead to injury. Educators should ensure their classrooms’ physical environments.'
  },
  {
    number: '2',
    text: 'The benefits of virtual reality in education are embraced by many educators, but some are still reluctant to use it in their classrooms. Reasons range from high costs to pushback from school administrators. Others see the value of both VR and AR as entertainment, but not as effective teaching tools in the classroom.'
  },
  {
    number: '3',
    text: 'Before looking into some of the benefits of virtual reality in education, let’s define what virtual reality is and how it differs from augmented reality. AR is used on a smart device to project a layer of educational text and lesson-appropriate content on top of a user’s actual surroundings'
  }
]
</script>
