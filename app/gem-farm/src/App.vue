<template>
  <div class="relative h-full min-h-screen">
    <!-- <TheNavBar /> -->
    <div class="pt-10 px-10 flex justify-center align-middle">
      <p class="text-4xl pt-3 mt-1 text-black underline">RASCAL</p>
      <img :width="50" :height="50" src="./assets/400x600.gif" />
      <p class="text-4xl pt-3 mt-1 px-2 text-black underline">LAND</p>
    </div>
    <!-- <div class="italic mt-5 text-center">by Gemworks</div> -->

    <div class="p-10">
      <!-- <router-view /> -->
      <Farmer />
    </div>

    <div class="pt-10"></div>
    <!-- <TheCat /> -->
    <!-- <TheFooter /> -->
  </div>
</template>

<script>
import Farmer from '@/views/Farmer.vue';
// import TheNavBar from '@/components/TheNavBar';
// import TheFooter from '@/components/gem-farm/TheFooter';
// import TheCat from '@/components/gem-farm/TheCat';
export default {
  components: { Farmer },
};
</script>

<style>
* {
  font-family: 'Press Start 2P', monospace;
}
input[type='radio']:checked + span {
  @apply text-black;
}
</style>
