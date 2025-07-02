<template>
  <div>
    <section class="bg-gray-100 shadow sm py-20">
        <div class="container mx-auto flex flex-col md:flex-row items-center px-28">
            <div class="w-full md:w-1/2 space-y-6">
                <p class="text-sm text-green-600 font-semibold">Start your favorite course</p>
                <h1 class="text 4xl md:text-5xl font-bold text-gray-700 leading-tight">Now learning from <br> anywhere, and build <br> your <span class="text-green-600">bright career.</span></h1>
                <p class="text-gray-600">
                    It has survived not only five centuries, but also <br> the leap into electronic typesetting.
                </p>
                <button class="bg-green-600 hover:bg-green-700 text-white font-semibold px-6 py-3 rounded-md">Start A Course</button>
            </div>
            <div class="w-full md:w-1/2 md:mt-0 flex justify-center relative">
                <img src="https://static.vecteezy.com/system/resources/thumbnails/054/040/037/small_2x/a-young-person-in-glasses-writes-in-a-book-wearing-an-orange-sweater-focused-on-their-studies-png.png" alt="hero" class="w-3/4 max-w-xl">
            </div>
        </div>
    </section>

    <section class="bg-white py-10">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center justify-between mb-6">
                <h2 class="text-2xl font-semibold text-gray-800">All <span class="text-green-600">Courses</span> of Edule</h2>
                <div class="mt-4 md:mt-0">
                    <input type="text" placeholder="Search course" class="border border-gray-300 px-4 py-2 rounded-md">
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
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="bg-white ml-6 mr-6 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="">
                <div class="p-4">
                    <h3 class="text-sm text-green-600 font-semibold">Design</h3>
                    <h2 class="text-lg font-semibold text-gray-800">Design Course</h2>
                    <p class="text-gray-600 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
                    <div class="text-green-600 font-semibold text-gray-800 text-lg mt-4">
                        <span class="text-green-600 font-semibold text-gray-800 text-lg mt-4">$100</span>
                        <span class="text-gray-600 font-semibold text-gray-800 text-sm mt-4 ml-1 line-through">$200</span>
                    </div>
                    <button class="bg-green-600 text-white px-6 py-3 mt-6 rounded-md hover:bg-green-700 transition">Learn More</button>
            </div>
        </div>
            <div class="bg-white ml-6 mr-6 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="">
                <div class="p-4">
                    <h3 class="text-sm text-green-600 font-semibold">Development</h3>
                    <h2 class="text-lg font-semibold text-gray-800">Design Course</h2>
                    <p class="text-gray-600 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
                    <div class="text-green-600 font-semibold text-gray-800 text-lg mt-4">
                        <span class="text-green-600 font-semibold text-gray-800 text-lg mt-4">Free</span>
                        <span class="text-gray-600 font-semibold text-gray-800 text-sm mt-4 ml-1 line-through">$200</span>
                    </div>
                    <button class="bg-green-600 text-white px-6 py-3 mt-6 rounded-md hover:bg-green-700 transition">Learn More</button>
            </div>
        </div>
            <div class="bg-white ml-6 mr-6 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="">
                <div class="p-4">
                    <h3 class="text-sm text-green-600 font-semibold">Marketing</h3>
                    <h2 class="text-lg font-semibold text-gray-800">Design Course</h2>
                    <p class="text-gray-600 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
                    <div class="text-green-600 font-semibold text-gray-800 text-lg mt-4">
                        <span class="text-green-600 font-semibold text-gray-800 text-lg mt-4">Free</span>
                    </div>
                    <button class="bg-green-600 text-white px-6 py-3 mt-6 rounded-md hover:bg-green-700 transition">Learn More</button>
            </div>
        </div>
            <div class="bg-white ml-6 mr-6 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="">
                <div class="p-4">
                    <h3 class="text-sm text-green-600 font-semibold">Business</h3>
                    <h2 class="text-lg font-semibold text-gray-800">Design Course</h2>
                    <p class="text-gray-600 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
                    <h3 class="text-green-600 font-semibold text-gray-800 text-lg mt-4">$100</h3>
                    <button class="bg-green-600 text-white px-6 py-3 mt-6 rounded-md hover:bg-green-700 transition">Learn More</button>
            </div>
        </div>
            <div class="bg-white ml-6 mr-6 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="">
                <div class="p-4">
                    <h3 class="text-sm text-green-600 font-semibold">Data Science</h3>
                    <h2 class="text-lg font-semibold text-gray-800">Design Course</h2>
                    <p class="text-gray-600 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
                    <h3 class="text-green-600 font-semibold text-gray-800 text-lg mt-4">$100</h3>
                    <button class="bg-green-600 text-white px-6 py-3 mt-6 rounded-md hover:bg-green-700 transition">Learn More</button>
            </div>
        </div>
            <div class="bg-white ml-6 mr-6 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="">
                <div class="p-4">
                    <h3 class="text-sm text-green-600 font-semibold">Cybersecurity</h3>
                    <h2 class="text-lg font-semibold text-gray-800">Design Course</h2>
                    <p class="text-gray-600 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
                    <h3 class="text-green-600 font-semibold text-gray-800 text-lg mt-4">$100</h3>
                    <button class="bg-green-600 text-white px-6 py-3 mt-6 rounded-md hover:bg-green-700 transition">Learn More</button>
            </div>
        </div>
        </div>
    </section>
    <button class="bg-green-100 border rounded-lg hover:bg-green-600 hover:text-white text-green-600 font-semibold px-6 py-3 rounded-md block mx-auto">Other Course</button>
  </div>
</template>

<script>
export default {
  layout: 'default',
}
</script>

<style>

</style>
