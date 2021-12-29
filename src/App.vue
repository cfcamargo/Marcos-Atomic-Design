<template>
  <div class="componenent">
    <Header />
    <Presentation />
    <Services />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation, Services } from '@/components/organisms'

export default defineComponent({
  components: { Header, Presentation, Services }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 1rem;
}
</style>
