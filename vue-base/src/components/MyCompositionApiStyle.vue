<script setup>
import { ref, onMounted } from 'vue'

// 响应式状态
const count = ref(0)

// 用来修改状态、触发更新的函数
function increment() {
  count.value++
}

// 生命周期钩子
onMounted(() => {
  console.log(`组合式API:The initial count is ${count.value}.`)
})
</script>

<template>
  <button @click="increment">组合式API：Count is: {{ count }}</button>
</template>