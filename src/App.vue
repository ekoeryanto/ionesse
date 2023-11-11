<script setup lang="ts">
import { IonApp, IonRouterOutlet } from '@ionic/vue'

useHead({
  title: 'Main',
  titleTemplate: '%s - Ionesse',
})
</script>

<template>
  <IonApp>
    <IonRouterOutlet />
  </IonApp>
</template>
