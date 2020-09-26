<template>
  <div>
    <p>hi {{ name }}</p>
    <p class="text-sm opacity-50">
      <em>dynamic.route</em>
    </p>

    <div>
      <button class="btn m-3 text-sm mt-8" @click="back">Back</button>
    </div>
  </div>
</template>

<script lang="ts">
import { useRouter } from 'vue-router'
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    name: String
  },
  setup() {
    const router = useRouter()
    const back = () => router.push('/')

    return {
      back
    }
  }
})
</script>
