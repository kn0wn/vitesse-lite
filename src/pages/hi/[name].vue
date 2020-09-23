
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

<script setup='props' lang='ts'>
import { useRouter } from "vue-router";

declare const props: {
  name: string;
};

const router = useRouter();
export const back = () => router.push("/");
</script>
