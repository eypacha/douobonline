<template>
  <div class="container">
    <DouobLogo/>
    <div>
      <p class="mx-auto text-base text-center text-[transparent]">douob is a system made by <a href="http://verne.studio">verne.studio</a> that allows us to connect and take control of the screens that surround us, shop windows, events, cinemas, exhibitions, museums and public roads. contact us for more information</p>
    </div>
  </div>
</template>

<script setup>
import DouobLogo from './components/DouobLogo.vue';

</script>

<style scoped lang="scss">

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  max-width: 600px;
}
</style>
