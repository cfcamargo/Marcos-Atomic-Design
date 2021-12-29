<template>
  <div class="componenent">
    <NavBar />
    <SearchForm />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavBar, SearchForm } from '@/components/molecules'

export default defineComponent({
  components: { NavBar, SearchForm }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 1rem;
}
</style>
