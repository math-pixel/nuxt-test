<template>
  <div>
    <img :src="URL" alt="" @click="emit('cliked')">

  </div>
</template>

<script setup>

const props = defineProps(['URL'])
const emit = defineEmits(['cliked'])

</script>