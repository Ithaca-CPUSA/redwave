<template>
  <div class="text-gray-600">
    <Navbar />
    <main class="mx-auto max-w-6xl">

      <article
        class="mx-auto mb-6 flex flex-col">
          <img class="object-cover max-h-[400px]" src="./assets/P1220527.JPG" alt="">
          <div
            class="text-brandWhite px-3 lg:px-5 py-5 bg-brandRed flex-1">
            <h2
              class="md:text-7xl sm:text-4xl text-2xl font-bold tracking-tight mb-2">
              Ithaca Celebrates Mayday</h2>
            <p class="pl-1 text-xs">May 1, 2024</p>
            <p class="pl-1 lg:text-xl">Morbi leo risus, porta ac consectetur ac, vestibulum
              at eros. Donec ullamcorper nulla non metus auctor fringilla.
              Maecenas sed diam eget risus varius blandit sit amet non magna.
              Duis mollis, est non commodo luctus, nisi erat porttitor ligula,
              eget lacinia odio sem nec elit.</p>
            </div>
      </article>

      <section class="px-3 xl:px-0">
        <h2 class="font-semibold text-3xl">Upcoming Events</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          <ArticleCard />
          <ArticleCard />
          <ArticleCard />
        </div>
      </section>
      <section>

      </section>
    </main>
  </div>
</template>

<script setup lang="ts">
import Navbar from './components/Navbar.vue';
import ArticleCard from './components/ArticleCard.vue';
</script>
