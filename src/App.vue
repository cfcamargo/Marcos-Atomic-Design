<template>
  <div class="componenent">
    <NavBar />
    <SearchForm />
    <SocialNetworks />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavBar, SearchForm, SocialNetworks } from '@/components/molecules'

export default defineComponent({
  components: { NavBar, SearchForm, SocialNetworks }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 1rem;
}
</style>
