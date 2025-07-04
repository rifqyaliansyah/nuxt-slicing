<template>
    <div>
        <div class="bg-gray-100 py-12 shadow sm pt-28">
            <h1 class="text-3xl text-gray-800 font-bold text-center mt-6">
            Browse All Courses
        </h1>
        <p class="text 2xl text-gray-600 text-center mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>
        </div>
        <CourseList />
        <CourseCard />
    </div>
</template>

<script>
import CourseList from '~/components/sections/CourseList.vue'
import CourseCard from '~/components/sections/CourseCard.vue'

export default {
    layout: 'default',
    components: {
        CourseList,
        CourseCard
    },
}
</script>

<style>
</style>