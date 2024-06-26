<script setup>
window.AWIN = window.AWIN || {}
window.AWIN.Tracking = window.AWIN.Tracking || {}
window.AWIN.Tracking.Sale = {}

window.AWIN.Tracking.Sale.amount = '12.5'
window.AWIN.Tracking.Sale.orderRef = '1234dsfdf'
window.AWIN.Tracking.Sale.parts = 'DEFAULT:12.5'
window.AWIN.Tracking.Sale.voucher = '1324'
window.AWIN.Tracking.Sale.currency = 'EUR'
window.AWIN.Tracking.Sale.test = '0'
window.AWIN.Tracking.Sale.channel = 'aw'

const imggg = document.createElement('img')
imggg.src =
  'https://www.awin1.com/sread.img?tt=ns&tv=2&merchant=14411&amount=' +
  window.AWIN.Tracking.Sale.amount +
  '&cr=' +
  window.AWIN.Tracking.Sale.currency +
  '&ref=' +
  window.AWIN.Tracking.Sale.orderRef +
  '&parts=DEFAULT:' +
  window.AWIN.Tracking.Sale.amount +
  '&vc=' +
  window.AWIN.Tracking.Sale.voucher +
  '&ch=aw&testmode=0'
document.body.appendChild(imggg)

const master = document.createElement('script')
master.src = 'https://www.dwin1.com/14411.js'
master.type = 'text/javascript'
master.defer = 'defer'
document.body.appendChild(master)
</script>

<template>
  <div id="test" class="about">
    <h1>This is a success page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
