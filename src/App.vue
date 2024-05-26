<template>
  <div class="text-brandGrey">
    <Navbar/>
    <main class="mx-auto max-w-6xl">
      <article
        class="mx-auto mb-6 relative flex items-center content-center justify-center overflow-hidden max-h-[648px]">
        <figure class="overflow-hidden">
          <img class="object-fill" src="./assets/P1220527.JPG" alt="">
          <figcaption
            class="text-brandWhite absolute bottom-0 left-0 right-0 p-5 bg-brandRed flex-1">
            <h2
              class="md:text-7xl sm:text-4xl text-2xl font-bold tracking-tight mb-2">
              Ithaca Celebrates Mayday</h2>
            <p class="pl-1 text-xs">May 1, 2024</p>
            <p class="pl-1">Ithaca did stuff</p>
          </figcaption>
        </figure>
      </article>

      <section class="px-3 xl:px-0">
        <h2 class="font-semibold text-3xl">Upcoming Events</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          <ArticleCard/>
          <ArticleCard/>
          <ArticleCard/>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup lang="ts">
import Navbar from './components/Navbar.vue';
import ArticleCard from './components/ArticleCard.vue';
</script>
