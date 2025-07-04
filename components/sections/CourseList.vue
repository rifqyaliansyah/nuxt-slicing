<template>
            <div class="container mx-auto px-12 mt-12">
            <div class="flex flex-col md:flex-row items-center justify-between mb-6">
                <h2 class="text-2xl font-semibold text-gray-800">All <span class="text-green-600">Courses</span> of Edule</h2>
                <div class="mt-4 md:mt-0 relative">
                    <input type="text" placeholder="Search course" class="border border-gray-300 pl-10 pr-4 py-2 rounded-md w-full">
                    <svg class="w-5 h-5 text-gray-500 absolute left-3 top-1/2 transform -translate-y-1/2 pointer-events-none" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-4.35-4.35m0 0A7.5 7.5 0 1116.65 5a7.5 7.5 0 010 11.65z" />
                    </svg>
                </div>
            </div>
            <div class="flex flex-wrap gap-4 mb-8 justify-center">
                <a href="#" class="text-gray-600 border border-gray-300 hover:text-green-600 hover:border-green-600 visited:text-green-600 visited:border-green-600 font-semibold px-4 py-2 rounded-md">All</a>
                <a href="#" class="text-gray-600 border border-gray-300 hover:text-green-600 hover:border-green-600 font-semibold px-4 py-2 rounded-md">Design</a>
                <a href="#" class="text-gray-600 border border-gray-300 hover:text-green-600 hover:border-green-600 font-semibold px-4 py-2 rounded-md">Development</a>
                <a href="#" class="text-gray-600 border border-gray-300 hover:text-green-600 hover:border-green-600 font-semibold px-4 py-2 rounded-md">Marketing</a>
                <a href="#" class="text-gray-600 border border-gray-300 hover:text-green-600 
                hover:border-green-600 font-semibold px-4 py-2 rounded-md">Business</a>
            </div>
        </div>
</template>