<script setup>
import { MainButton, useWebAppPopup } from 'vue-tg'

const { showAlert } = useWebAppPopup()
</script>

<template>
  <div>
    <h1>
      Welcome to Ton Delivery!
    </h1>
    <MainButton text="Open alert" @click="() => showAlert('Hello!')" />
  </div>
</template>
