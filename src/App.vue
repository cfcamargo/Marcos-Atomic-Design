<template>
  <div class="componenent">
    <HomePage />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { HomePage } from '@/components/pages'


export default defineComponent({
  components: { HomePage }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 1rem;
}
</style>
