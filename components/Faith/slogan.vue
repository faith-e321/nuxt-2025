<template>
    <div>
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