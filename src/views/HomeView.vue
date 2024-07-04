<script setup>
import { SovendusLandingPage } from 'sovendus-voucher-network-and-checkout-benefits-vue'
import TheWelcome from '../components/TheWelcome.vue'
const master = document.createElement('script')
master.src = 'https://www.dwin1.com/14411.js'
master.type = 'text/javascript'
master.defer = 'defer'
document.body.appendChild(master)
</script>

<template>
  <main>
    <TheWelcome />
    <SovendusLandingPage />
  </main>
</template>
