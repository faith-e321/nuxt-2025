<template>
    <div class="text-4xl text-red-400">
        {{ message }}
    </div>
</template>
    <script setup>
        defineProps({
            message: {
                default: "I really love HTML",
            },
        });
    </script>