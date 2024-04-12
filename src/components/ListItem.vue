<script setup>
defineProps({
  text: String,
  active: {
    type: Boolean,
    default: false
  }
})

const defaultClasses = 'font-sans font-medium text-sm md:text-lg text-center text-dull'
const activeClasses = 'font-sans font-semibold text-sm md:text-lg text-center text-white'
</script>

<template>
  <li :class="active ? activeClasses : defaultClasses">
    {{ text }}
  </li>
</template>
