<template>
    <div class="buttons">
      <button @click="decreaseCount">-</button>
      <button @click="increaseCount">+</button>
    </div>
</template>

<script setup>
import { useCounterStore } from '@/stores/counter';

const store = useCounterStore()

const { increaseCount, decreaseCount } = store
</script>
