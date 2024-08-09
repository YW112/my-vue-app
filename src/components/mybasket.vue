<script setup>
const props = defineProps ({
    title: String,
    price: Number,
    isAdded: Boolean
})
</script>

<template>
    <div class="bask-prod">
        <h2>Товар: {{ title }} </h2>
        <h3>Цены: {{ price }} </h3>
        <h3> Добавлен: {{ isAdded }} </h3>
    </div>
</template>

<style>
.bask-prod {
    border: 1px solid blue;
    color: black;
}
</style>