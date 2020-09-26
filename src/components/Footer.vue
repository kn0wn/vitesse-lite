<template>
  <div class="text-xl mt-6">
    <div class="icon-btn mx-2" @click="isDark = !isDark">DM</div>

    <a class="icon-btn mx-2" href="https://github.com/antfu/vitesse" target="_blank"> G </a>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { isDark } from '/@/utils'

export default defineComponent({
  setup() {
    return { isDark }
  }
})
</script>
