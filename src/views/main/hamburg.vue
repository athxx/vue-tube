<template>
  <Button />
  <svg
    xmlns="http://www.w3.org/2000/svg"
    fill="none"
    viewBox="0 0 24 24"
    stroke="currentColor"
    className="h-6 w-6"
  >
    <path
      className="transition-all duration-200"
      strokeLinecap="round"
      strokeLinejoin="round"
      strokeWidth="{1.8}"
      d="M4 6h16M4 12h16M4 18h16"
    />
  </svg>
</template>
<script setup lang="ts">
import Button from '../common/button.vue'
</script>
