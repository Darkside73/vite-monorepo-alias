<script setup lang="ts">
import { useHello } from '@/composable/useHello'

const hello = useHello('Vite')
</script>

<template>
  <div>
    {{ hello }}
  </div>
</template>
