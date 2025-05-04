<template>
    <div class="pb-4">
        <h1 class="text-2xl border-b border-gray-200 pb-4">{{ title }}</h1>
    </div>
</template>
<script setup>
const props = defineProps({
    title: {
        type: String,
        default: 'Welcome to my website',
    }
})
</script>