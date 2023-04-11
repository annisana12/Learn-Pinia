<template>
    <div>
        <h3>Edit counter:</h3>
        <input v-model="store.count" type="number">
    </div>
</template>

<script setup>
import { useCounterStore } from '../stores/counter';

const store = useCounterStore()
</script>
