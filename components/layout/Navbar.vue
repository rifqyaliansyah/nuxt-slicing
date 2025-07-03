<template>
    <header class="bg-gray-100 shadow sm">
        <div class="container mx-auto flex items-center justify-between py-4 px-12">
            <div class="text-2xl font-bold text-green-600"><span class="text-gray-700">Edu</span>le</div>
            <nav class="space-x-8 hidden md:flex">
                <NuxtLink to="/" class="text-gray-700 visited:text-green-600 hover:text-green-600 font-semibold">Home</NuxtLink>
                <NuxtLink to="/course" class="text-gray-700 hover:text-green-600 font-semibold">All Courses</NuxtLink>
                <a href="#" class="text-gray-700 hover:text-green-600 font-semibold">Pages</a>
                <a href="#" class="text-gray-700 hover:text-green-600 font-semibold">Blog</a>
                <a href="#" class="text-gray-700 hover:text-green-600 font-semibold">Contact</a>
            </nav>
            <div class="space-x-4">
                <a href="#" class="text-gray-700 font-semibold hover:text-green-600">Sign In</a>
                <a href="#" class="bg-white text-gray-700 px-4 py-2 rounded-md font-semibold hover:text-green-600 border border-gray-300">Sign Up</a>
            </div>
        </div>
    </header>
</template>