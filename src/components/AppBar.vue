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
            @click.stop="drawer = !drawer"
            size="x-large"
            class="nav-icon-right"
            :ripple="false"
          ></v-app-bar-nav-icon>
        </v-col>
      </v-row>
    </v-container>
  </v-app-bar>

  <v-navigation-drawer
    v-model="drawer"
    temporary
  >
    <v-list :items="items"></v-list>
  </v-navigation-drawer>
</template>

<script setup>
import { ref, watch } from 'vue'

const drawer = ref(false)
const group = ref(null)

const items = [
  {
    title: 'Foo',
    value: 'foo'
  },
  {
    title: 'Bar',
    value: 'bar'
  },
  {
    title: 'Fiz',
    value: 'fiz'
  },
  {
    title: 'Buzz',
    value: 'buzz'
  }
]

watch(group, () => {
  drawer.value = false
})
</script>
