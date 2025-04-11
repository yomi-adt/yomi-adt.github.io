<script setup>
import { Divider } from 'primevue';
</script>

<template>
    <div class="flex-container">
        <div class="flex-item">
            <p1>yomi-adt</p1>
        </div>
        <div class="flex-item">
            <p1>yomi-adt</p1>
        </div>
    </div>

    <Divider />
</template>

<style scoped>
    .flex-container {
        display: flex;
        justify-content: space-between;
    }

    .flex-item {
        align-items: flex-start;
    }

    .flex-item-end {
        align-items: flex-end;
        padding: 1%;
    }
</style>