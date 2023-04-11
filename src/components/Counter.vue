<template>
    <div class="count">
        {{ count }}
    </div>
</template>

<script setup>
import { storeToRefs } from 'pinia';
import { useCounterStore } from '../stores/counter';

const store = useCounterStore()

const { count } = storeToRefs(store)
</script>
