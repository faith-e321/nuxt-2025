<template>
    <div>
        <PageHeader title="Contact" />
    </div>
    <Hero 
        Heading="Want to drop me a note?" 
        Subtitle="Send me a message here!" 
        Link="/about"
        LinkName="Learn more about me"
        style="background-image: url('https://images.unsplash.com/photo-1745750747234-9584cbd65358?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');" />
    <div class="grid grid-col-1 gap-4 pt-4">
        <label>Your Name</label>
        <input class="h-10 bg-gray-100 rounded border p-4 border-gray-300"></input>

        <label>Subject Line</label>
        <input class="h-10 bg-gray-100 rounded border p-4 border-gray-300"></input>

        <label>Your Message</label>
        <textarea class="h-64 bg-gray-100 rounded border p-4 border-gray-300"></textarea>

        <button class="p-4 max-w-32 bg-purple-200 rounded hover:bg-purple-700 hover:text-gray-100">Send</button>
    </div>
</template>