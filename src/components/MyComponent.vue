<template>
  <div id="demo">
    <label for="">teste</label>
    <!-- <button v-on:click="show = !show">
      Toggle
    </button>
    <transition name="fade">
      <p v-if="show">Olá</p>
    </transition> -->
  </div>
</template>
<script>
export default {
  el: '#demo',
  data: {
    show: true
  }
}
</script>
<style>
.fade-enter-active, .fade-leave-active {
  transition: opacity .5s
}
.fade-enter, .fade-leave-to  {
  opacity: 0
}
</style>
