<template>
  <div class="relative h-full min-h-screen">
    <!-- <TheNavBar /> -->
    <div class="pt-10 px-10 flex justify-center align-middle">
      <p class="text-4xl pt-3 mt-1 text-black underline">RASCAL LAND</p>
    </div>
    <div class="italic mt-5 text-center">by Gamedust</div>

    <div class="p-10">
      <router-view />
    </div>

    <div class="pt-10"></div>
    <!-- <TheFooter /> -->
  </div>
</template>

<script>
import TheNavBar from '@/components/TheNavBar';
import TheFooter from '@/components/gem-farm/TheFooter';
export default {
  components: {},
};
</script>

<style>
input[type='radio']:checked + span {
  @apply text-black;
}
</style>
