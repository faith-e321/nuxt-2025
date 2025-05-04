<template>
    <div>
        <PageHeader title="Contact" />
    </div>
    <div class="grid grid-col-1 gap-4">
        <p class="italic">Want to drop a note? Send me a message here!</p>

        <label>Your Name</label>
        <input class="h-10 bg-gray-100 rounded border p-4 border-gray-300"></input>

        <label>Subject Line</label>
        <input class="h-10 bg-gray-100 rounded border p-4 border-gray-300"></input>

        <label>Your Message</label>
        <textarea class="h-64 bg-gray-100 rounded border p-4 border-gray-300"></textarea>

        <button class="p-4 max-w-32 bg-purple-200 rounded hover:bg-purple-700 hover:text-gray-100">Send</button>
    </div>
</template>