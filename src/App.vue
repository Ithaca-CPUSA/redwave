<template>
  <div class="text-gray-600">
    <Navbar />
    <main class="">
      <HeroSection />
      <CardGrid />
      <section class="my-24">
        <div class="mx-auto max-w-6xl text-center">
          <h2 class="text-3xl mb-6">Did you know there is a Communist Party here
            in
            Ithaca?</h2>
          <div class="mx-auto max-w-4xl mb-6">
            <p>Vestibulum id ligula porta felis euismod semper. Cum sociis
              natoque
              penatibus et magnis dis parturient montes, nascetur ridiculus mus.
              Cras mattis consectetur purus sit amet fermentum. Maecenas sed
              diam
              eget risus varius blandit sit amet non magna. Lorem ipsum dolor
              sit
              amet, consectetur adipiscing elit. Integer posuere erat a ante
              venenatis dapibus posuere velit aliquet.</p>
          </div>
          <a href="" class="text-white bg-brandRed px-4 py-2 uppercase">Get in
            touch</a>
        </div>
      </section>
      <CardGrid heading="Latest from People's World"
        class="bg-brandBlue text-white" />
      <section class="my-24">
        <div class="mx-auto max-w-6xl px-4 xl:px-0">
          <h2 class="text-4xl font-semibold">The Party In Action</h2>
          <article class="my-12 grid grid-cols-12 gap-4">
            <div class="col-span-7">
              <h3 class="font-semibold text-2xl mb-4">Just Cause Rally</h3>
              <time class="block" datetime="2024-01-01">Jan 1, 2024</time>
              <p>Aenean lacinia bibendum nulla sed consectetur. Curabitur
                blandit
                tempus porttitor. Cras mattis consectetur purus sit amet
                fermentum. Maecenas sed diam eget risus varius blandit sit amet
                non magna.</p>
            </div>
            <div class="col-span-5">
              <img src="./assets//P1220527.JPG" class="object-contain" alt="">
            </div>
          </article>
        </div>
      </section>
      <NewsletterSignup />
    </main>
    <SiteFooter />
  </div>
</template>

<script setup lang="ts">
import Navbar from './components/Navbar.vue';
import HeroSection from './components/HeroSection.vue';
import CardGrid from './components/CardGrid.vue';
import NewsletterSignup from './components/NewsletterSignup.vue';
import SiteFooter from './components/SiteFooter.vue';
</script>
