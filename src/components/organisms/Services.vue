<template>
  <div class="services">
    <Service
      title="Front end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia incidunt dignissimos nihil maxime! Iusto id totam, vero illum sequi minima. Doloremque explicabo ipsa velit dolores fugiat et esse a corrupti."
    />
    <Service
      title="Back end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia incidunt dignissimos nihil maxime! Iusto id totam, vero illum sequi minima. Doloremque explicabo ipsa velit dolores fugiat et esse a corrupti."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia incidunt dignissimos nihil maxime! Iusto id totam, vero illum sequi minima. Doloremque explicabo ipsa velit dolores fugiat et esse a corrupti."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
