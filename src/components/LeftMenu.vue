<template lang="pug">
#left-menu
  h1 新しい歌
  table
    tr(
      v-for="(club, i) in clubs"
      :key="i"
    )
      td
        router-link(:to="club.path") {{ club.name }}
</template>

<script setup>
const clubs = [
  { path: '/guitar', name: 'お' },
  { path: '/dance', name: 'か' },
  { path: '/dance', name: 'て' },
  { path: '/dance', name: 'ゆ' },
  { path: '/dance', name: 'ぴ' }
]
</script>
