<template>
    <footer class="my-4">
      <div class="mx-auto max-w-6xl px-4 xl:px-0">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <LogoLockup class="md:mb-20"/>
        <nav class="col-span-2 flex flex-col md:flex-row">
          <NavItem href="https://cpusa.org">National Party Website</NavItem>
          <NavItem href="https://cpusa.org">National Party Website</NavItem>
          <NavItem href="https://cpusa.org">National Party Website</NavItem>
        </nav>
        </div>
      </div>
      <div class="mx-auto max-w-6xl px-4 xl:px-0 py-4 flex flex-col md:flex-row justify-between items-center content-center">
        <p class="text-xs text-gray-400 my-2">Copyright &copy; 2024 Communist Party USA - Ithaca Club.</p>
        <SocialMenu class="my-2"/>
      </div>
    </footer>
</template>
<script setup lang="ts">
import LogoLockup from './LogoLockup.vue';
import NavItem from './NavItem.vue';
import SocialMenu from './SocialMenu.vue';
</script>
