<template>
  <header class="py-8 sticky">
      <div class="mx-auto md:max-w-6xl flex items-center justify-between px-4 xl:px-0">

      <div class="flex items-center">
        <button class="block md:hidden mr-4 flex flex-col items-center"
          @click="showMobileMenu">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"
            fill="currentColor" class="size-6">
            <path fill-rule="evenodd"
              d="M3 6.75A.75.75 0 0 1 3.75 6h16.5a.75.75 0 0 1 0 1.5H3.75A.75.75 0 0 1 3 6.75ZM3 12a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75A.75.75 0 0 1 3 12Zm0 5.25a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75Z"
              clip-rule="evenodd" />
          </svg>
          <span class="sr-only">
            menu
          </span>
        </button>
        <LogoLockup/>
      </div>
      <div class="flex flex-col">
        <SocialMenu class="hidden md:block"/>
      <div class="flex items-center">
        <nav class="flex items-center hidden md:block">
          <NavItem href="/articles">About</NavItem>
          <NavItem href="/articles">Articles</NavItem>
          <NavItem href="/events">Events</NavItem>
          <NavItem href="/events">Get Involved</NavItem>
        </nav>
        <a href="/donate"
          class="bg-brandRed px-8 py-2 rounded-sm text-brandWhite font-semibold uppercase">Donate</a>
      </div>
      </div>
      </div>
    </header>
</template>

<script setup lang="ts">
import LogoLockup from './LogoLockup.vue';
import NavItem from './NavItem.vue';
import SocialMenu from './SocialMenu.vue'
</script>
