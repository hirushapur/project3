<template>
  <q-layout view="lHh Lpr lFf">


    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup>
import { ref } from 'vue'


defineOptions({
  name: 'MainLayout'
})


</script>
