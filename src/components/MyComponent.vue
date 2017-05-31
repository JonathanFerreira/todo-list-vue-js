<template>
  <div v-if="new Date().getHours() <= 13 && new Date().getHours() >= 7">
     Bom dia
  </div>
  <div v-else-if="new Date().getHours() > 13 && new Date().getHours() <= 18 ">
   Boa tarde
  </div>
  <div v-else>
   Boa noite
  </div>
</template>

<script>
</script>

<style>
</style>
