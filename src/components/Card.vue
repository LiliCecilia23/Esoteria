<script setup>
    const props = defineProps(['front', 'deck'])
</script>
<template>
  <div>
    <img style="height: 200px; border-radius: 5%;" :src="`decks/${deck}/${front}`" />
  </div>
</template>
