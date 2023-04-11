<template>
  <div class="about">
    <h1>About</h1>
    <button @click="store.increaseCount" class="counter-button">
      {{ store.count }}
    </button>
  </div>
</template>

<script setup>
import { useCounterStore } from '../stores/counter';

const store = useCounterStore()
</script>

<style>
.counter-button {
  margin-top: 20px;
  font-size: 50px;
  cursor: pointer;
}
</style>
