<template>
  <div>
    <Hero />
    <section class="section">
      <div class="container">
        <h1 class="title">Featured Courses</h1>
        <div class="columns">
          <div class="column is-one-quarter">
            <CourseCard />
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <h1 class="title">Featured Articles</h1>
        <div class="columns">
          <div class="column is-one-quarter">
            <BlogCard />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import CourseCard from '@/components/shared/CourseCard'
import BlogCard from '@/components/shared/BlogCard'
import Hero from '@/components/shared/Hero'

  export default {
    components: {
      CourseCard,
      BlogCard,
      Hero
    }
  }
</script>

<style lang="scss" scoped>
// card item

// card item end

// hero

// hero

  // Home page
.links {
  padding-top: 15px;
}
</style>