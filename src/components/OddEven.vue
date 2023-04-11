<template>
    <div>
      This counter is: {{ oddOrEven }}
    </div>
</template>

<script setup>
import { storeToRefs } from 'pinia';
import { useCounterStore } from '../stores/counter';

const store = useCounterStore()

const { oddOrEven } = storeToRefs(store)
</script>
