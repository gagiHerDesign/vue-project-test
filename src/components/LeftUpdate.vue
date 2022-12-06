<template lang="pug">
#left-update recent update_ {{ date }}
</template>

<script setup>
const date = new Date().toLocaleDateString()
</script>
