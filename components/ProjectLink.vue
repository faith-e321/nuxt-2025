<template>
    <div class="bg-gray-300/80 rounded-lg flex-row content-end">
        <div class="bg-gray-500/80 p-4 rounded-b-lg">
            <h1 class="text-2xl font-bold pb-2 text-white">{{ ProjectName }}</h1>
            <p class="italic pb-4 text-white">{{ ProjectDesc }}</p>
            <button class="p-4 bg-purple-200 rounded hover:bg-purple-700 hover:text-gray-100">View Project</button>
        </div>
    </div>
</template>
<script setup>
const props = defineProps({
ProjectName: {
    type: String,
    default: 'Project Title',
},
ProjectDesc: {
    type: String,
    default: 'Description',
}
})
</script>