<script setup>
    defineProps(['front', 'deck'])
</script>
<template>
  <div>
    <img testeroni="this is a test" style="height: 200px; border-radius: 5%;" :src="`decks/${deck}/${front}`" />
  </div>
</template>
