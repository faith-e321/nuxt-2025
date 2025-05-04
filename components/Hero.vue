<template>
    <section class="bg-cover bg-no-repeat h-96 rounded-xl object-bottom" style="background-image: url('https://images.unsplash.com/photo-1741761446510-7804410eade3?q=80&w=1750&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');">
        <article class="bg-gray-800/50 h-full w-full flex flex-col p-16 items-start justify-center text-white rounded-xl">
            <h1 class="text-4xl font-bold">{{ Heading }}</h1>
            <p class="italic text-lg">{{ Subtitle }}</p>
            <nuxt-link :to="Link">
                <button class="my-8 p-4 bg-purple-200 text-gray-900 rounded hover:bg-purple-700 hover:text-gray-100"> {{ LinkName }}</button>
        </nuxt-link>
        </article>
    </section>
</template>
<script setup>
const props = defineProps({
Heading: {
    type: String,
    default: 'Heading',
},
Subtitle: {
    type: String,
    default: 'Subtitle',
},
Link: {
    type: String,
    default: '/',
  },
LinkName: {
   type: String,
   default: 'Text', 
}
})
</script>