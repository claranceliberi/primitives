<script setup lang="ts">
import { OkuAspectRatio } from '@oku-ui/aspect-ratio'
</script>

<template>
  <div>
    <div class="w-[300px] rounded-sm overflow-hidden">
      <OkuAspectRatio :ratio="16 / 9">
        <img
          class="object-cover w-full h-full rounded-lg"
          src="https://images.unsplash.com/photo-1535025183041-0991a977e25b?w=300&dpr=2&q=80"
          alt="Landscape photograph by Tobias Tullius"
        >
      </OkuAspectRatio>
    </div>
  </div>
</template>
