<script setup>
useHead({
  link: [
    { rel: 'icon', type:  'image/png', href: '/favicon-.png'  }
  ]
});
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    <!-- <NuxtWelcome /> -->
  </div>
</template>