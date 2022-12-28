<template>
  <div class="relative h-full min-h-screen">
    <!-- <TheNavBar /> -->
    <div class="bg-white">
      <div class="mx-auto max-w-7xl pt-10 px-4 sm:px-6 lg:px-8">
        <div class="text-center">
          <p
            class="
              mt-1
              text-4xl
              font-bold
              tracking-tight
              text-gray-900
              sm:text-5xl
              lg:text-6xl
            "
          >
            Rascal Land
          </p>
          <h2 class="text-lg pt-1 font-semibold text-indigo-600 italic">
            by Gamedust
          </h2>
        </div>
      </div>
    </div>

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
