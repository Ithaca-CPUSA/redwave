<template>
  <div class="text-gray-600">
    <Navbar />
    <main class="">
      <section class="mx-auto max-w-6xl">
        <article class="mx-auto mb-6 flex flex-col">
          <img class="object-cover max-h-[400px]" src="./assets/P1220527.JPG"
            alt="">
          <div class="text-brandWhite px-3 lg:px-5 py-5 bg-brandRed flex-1">
            <h2
              class="md:text-7xl sm:text-4xl text-2xl font-bold tracking-tight mb-2">
              Ithaca Celebrates Mayday</h2>
            <p class="pl-1 text-xs">May 1, 2024</p>
            <p class="pl-1 lg:text-xl">Morbi leo risus, porta ac consectetur ac,
              vestibulum
              at eros. Donec ullamcorper nulla non metus auctor fringilla.
              Maecenas sed diam eget risus varius blandit sit amet non magna.
              Duis mollis, est non commodo luctus, nisi erat porttitor ligula,
              eget lacinia odio sem nec elit.</p>
          </div>
        </article>
      </section>

      <section class="px-3 xl:px-0 mx-auto max-w-6xl">
        <h2 class="font-semibold text-3xl">Upcoming Events</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          <ArticleCard />
          <ArticleCard />
          <ArticleCard />
        </div>
      </section>
      <section class="bg-brandBlue text-brandWhite py-12">
        <div class="mx-auto max-w-6xl px-4 xl:px-0">
          <h2 class="text-4xl font-semibold tracking-tight">Sign up for our Newsletter</h2>
          <form action="/newsletter-signup">
            <div class="my-4">
            <label class="text-xs block" for="email">Email</label>
            <input class="my-2" type="email" name="email" id="newsletter-email">
            </div>
            <button class="px-4 py-2 bg-white rounded-sm shadow-lg text-brandRed font-semibold uppercase" type="submit">Sign up</button>
          </form>
        </div>
      </section>
    </main>
    <SiteFooter/>
  </div>
</template>

<script setup lang="ts">
import Navbar from './components/Navbar.vue';
import SiteFooter from './components/SiteFooter.vue';
import ArticleCard from './components/ArticleCard.vue';
</script>
