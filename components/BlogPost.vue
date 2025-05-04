<template>
    <div class="border-y p-4">
        <h1 class="text-2xl font-bold">{{ BlogTitle }}</h1>
        <p class="text-gray-400 pb-2">{{ BlogDate }}</p>
        <p class="italic pb-2">{{ BlogExcerpt }} ...</p>
        <button class="hover:text-purple-800 hover:underline">Read More</button>
    </div>
</template>
<script setup>
const props = defineProps({
    BlogTitle: {
        type: String,
        default: 'Title',
    },
    BlogDate: {
        type: String,
        default: 'The Future',
    },
    BlogExcerpt: {
        type: String,
        default: 'Here is an excerpt',
    }
})
</script>