<template>
  <div class="flex items-center justify-center h-120">
    <h1 class="text-5xl">
      {{ $t('pages.staff.title') }}
    </h1>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  components: {},
  head() {
    return { title: this.$t('pages.staff.title') }
  }
})
</script>

<style></style>
