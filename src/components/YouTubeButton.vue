<template>
  <a
    :href="href"
    target="_blank"
    class="px-3 py-2 rounded-xl text-white font-semibold bg-red-600 hover:bg-red-700 transition-colors"
  >
    <slot>YouTube</slot>
  </a>
</template>

<script setup>
const props = defineProps({
  href: String,
});
</script>
