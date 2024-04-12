<script setup>
defineProps({
  text: String,
  active: {
    type: Boolean,
    default: false
  }
})

const defaultClasses =
  'font-sans font-medium text-lg leading-6 tracking-tighter text-center text-dull'
const activeClasses =
  'font-sans font-semibold text-lg leading-6 tracking-tighter text-center text-white'
</script>

<template>
  <li :class="active ? activeClasses : defaultClasses">
    {{ text }}
  </li>
</template>
