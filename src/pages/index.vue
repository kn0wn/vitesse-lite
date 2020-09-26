<template>
  <div>
    <p>
      <a href="https://github.com/antfu/vitesse" target="_blank"> Vitesse </a>
    </p>
    <p class="text-sm opacity-50">
      <em>intro</em>
    </p>

    <div class="py-4" />

    <input
      v-model="name"
      placeholder="What's your name"
      class="px-4 py-2 border border-gray-200 rounded text-center text-sm outline-none active:outline-none bg-transparent dark:border-gray-700"
      style="width: 250px"
      @keydown.enter="go"
    />

    <div>
      <button class="btn m-3 text-sm" :disabled="!name" @click="go">go</button>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { ref } from 'vue'
import { useRouter } from 'vue-router'

export default defineComponent({
  setup() {
    const name = ref('')
    const router = useRouter()
    const go = () => {
      if (name.value) router.push(`/hi/${name.value}`)
    }

    return {
      go,
      name
    }
  }
})
</script>
