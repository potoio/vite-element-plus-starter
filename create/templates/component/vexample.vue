<template>
  <div class="v-example">
    <slot />
  </div>
</template>

<script lang="ts" setup>
import { onMounted } from 'vue'

const props = defineProps({
  example: {
    type: String,
    required: true,
    default: ''
  }
})

onMounted(() => {
  console.log(props.example)
})
</script>

<style lang="scss" scoped>
.v-example {
  display: flex;
}
</style>
