<template>
  <div class="home-page">
      <HomeTemplate />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { HomeTemplate } from '@/components/templates'

export default defineComponent({
    components: { HomeTemplate }
})
</script>
