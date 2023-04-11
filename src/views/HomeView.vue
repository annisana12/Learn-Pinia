<template>
  <div class="home">
    <Counter />
    <Buttons />

    <hr>
    <OddOrEven />
    <hr>

    <CounterInput />
  </div>
</template>

<script setup>
import Buttons from '@/components/Buttons.vue'
import Counter from '@/components/Counter.vue'
import CounterInput from '@/components/CounterInput.vue'
import OddOrEven from '@/components/OddEven.vue'
</script>

<style>
div {
  margin: 10px 0;
}

.count {
  font-size: 60px;
  margin: 20px;
}

.buttons button {
  font-size: 40px;
  margin: 10px;
}
</style>
