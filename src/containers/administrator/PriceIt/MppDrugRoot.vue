<template>
  <transition name="slide-y-transition">
    <router-view class="full-height"></router-view>
  </transition>
</template>

<script>
  export default {
    name: 'mpp-drug',
  }
</script>
