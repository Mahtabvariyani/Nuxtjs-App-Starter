<script setup>
const links = [ {
  label: 'Home',
  icon: 'i-heroicons-home',
  to: '/'
}, {
  label: 'Events',
  icon: 'i-heroicons-chart-bar',
  to: '/events'
},]
</script>

<template>
  <UVerticalNavigation :links="links"  class=""/>
</template>

