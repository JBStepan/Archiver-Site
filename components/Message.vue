<script setup>

defineProps({
    content: String,
    user: String
})
</script>

<template>
    <div>
        <p>{{content}}</p>
        <p>Sent by: {{user}}</p>
    </div>
</template>

<style>
div {
    position: relative;
    width: 200px;
    border: 1px solid black;
}

p {
    word-wrap: normal;
    font: 500;
    font-family: sans-serif;
}
</style>