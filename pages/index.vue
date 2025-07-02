<template>
  <div>
    <sections-HeroSection />
    <sections-CourseList />
    <sections-CourseCard />
  </div>
</template>

<script>
import HeroSection from '~/components/sections/HeroSection.vue'
import CourseList from '~/components/sections/CourseList.vue'
import CourseCard from '~/components/sections/CourseCard.vue'

export default {
  components: {
    'sections-HeroSection': HeroSection,
    'sections-CourseList': CourseList,
    'sections-CourseCard': CourseCard
  },
  layout: 'default'
}
</script>

<style>

</style>
