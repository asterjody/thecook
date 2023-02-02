<template>
  <header
    class="bg-black/90 shadow-md h-16 flex justify-between items-stretch sticky top-0 z-50"
  >
    <router-link
      :to="{ name: 'home' }"
      class="inline-flex items-center h-full px-5 text-4xl text-white/90 font-bold"
    >
      TheC<span class="text-yellow-400">oo</span>k
    </router-link>
    <div class="flex items-center gap-1">
      <router-link
        :to="{ name: 'byName' }"
        class="inline-flex items-center px-2 h-full transition-colors text-sm text-center text-white/90 font-semibold hover:bg-yellow-400 hover:text-white md:text-base"
      >
        Search Meals
      </router-link>
      <router-link
        :to="{ name: 'byLetter' }"
        class="inline-flex items-center px-2 h-full transition-colors text-sm text-center text-white/90 font-semibold hover:bg-yellow-400 hover:text-white md:text-base"
      >
        Meals By Letter
      </router-link>
      <router-link
        :to="{ name: 'ingredients' }"
        class="inline-flex items-center px-2 h-full transition-colors text-sm text-center text-white/90 font-semibold hover:bg-yellow-400 hover:text-white md:text-base"
      >
        Meals By Ingredients
      </router-link>
    </div>
  </header>
</template>
