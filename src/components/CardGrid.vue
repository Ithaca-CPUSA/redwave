<template>
    <section class="py-8">
        <div class="px-3 xl:px-0 mx-auto max-w-6xl">
            <h2 class="font-semibold text-3xl">Upcoming Events</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <ArticleCard />
                <ArticleCard />
                <ArticleCard />
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import ArticleCard from './ArticleCard.vue';
</script>
