<template>
    <div>
    <div>
        <PageHeader title="About" />
    </div>
    <div class="flex gap-8 justify-stretch">
        <div class="w-fit">
            <img src="/FaithSnow.jpeg" alt="Faith in the Snow" class="h-80 w-80 rounded">
        </div>
        <div class="w-fit">
            <h1 class="font-bold text-2xl pb-2">Hello, my name is Faith Ahola!</h1>
            <p>I am a senior UX Design major at Northwest University where I am actively involved in creating culture for my campus through student leadership. My journey in UX began during my senior year of high school and has been kindled through research by way of podcasts, books, articles, and experience in the field – most recently through an internship with The Home Depot. <br> My motivation for this field is deep-rooted in life experience. Growing up, I acted as “tech-support” for my family and routinely saw room for improvement in the applications I came into frequent contact with. I have also actively served in church and developed a passion for raising up those around me. As I've moved into adulthood, I've become more broadly aware of how little changes can make big impacts in people’s work, enjoyment, and lives.</p>
        </div>
    </div>
    <div class="p-4"></div>
    <div>
        <h1 class="font-bold text-2xl pb-4">My Skills</h1>
        <div class="grid grid-cols-2 gap-4">
            <div class="italic">Verbal and Written Communication</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 90%"></div>
            </div>
            <div class="italic">Data Collection</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 70%"></div>
            </div>
            <div class="italic">User Research</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 80%"></div>
            </div>
            <div class="italic">Computer Literacy and Troubleshooting</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 90%"></div>
            </div>
            <div class="italic">Presentation</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 85%"></div>
            </div>
            <div class="italic">File Management</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 80%"></div>
            </div>
            <div class="italic">HTML & CSS</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 70%"></div>
            </div>
            <div class="italic">Active Listening</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 90%"></div>
            </div>
            <div class="italic">Team Collaboration</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 95%"></div>
            </div>
            <div class="italic">Time Management</div>
            <div class="w-full bg-gray-200 rounded-full h-3">
                <div class="bg-green-600 h-3 rounded-full" style="width: 85%"></div>
            </div>
        </div>
        <div class="pt-4">
            <h1 class="font-bold text-2xl pb-4">Experience and Education</h1>
            <div class="grid grid-flow-col auto-cols-max justify-between">
                <div>
                    <h2 class="text-xl font-semibold">Northwest University</h2>
                    <p>B.A. User Experience Design</p>
                    <div class="h-4"></div>
                    <h2 class="text-xl font-semibold">Clark College</h2>
                    <p>A.A. General Studies</p>
                </div>
                <div>
                    <h2 class="text-xl font-semibold">The Home Depot</h2>
                    <p>UX Design Intern</p>
                    <ul class="italic list-disc pl-8">
                        <li>Task 1</li>
                        <li>Task 2</li>
                        <li>Task 3</li>
                    </ul>
                    <div class="h-4"></div>
                    <h2 class="text-xl font-semibold">Northwest University</h2>
                    <p>Graphic Design and Social Media Coordinator</p>
                    <ul class="italic list-disc pl-8">
                        <li>Task 1</li>
                        <li>Task 2</li>
                        <li>Task 3</li>
                    </ul>
                </div>
            </div>
        </div>
        <ProjectsButton />
    </div>
    </div>
</template>