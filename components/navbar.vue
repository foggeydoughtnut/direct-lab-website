<template>
  <div>
    <div class="flex flex-row border-b shadow-md py-4"> <!-- Desktop Mode -->
      <div class="flex-1 ml-4">
        <NuxtLink to="/" class=" rounded-xl p-2 md:px-6 hover:shadow-lg transition-all delay-75 duration-300 text-lg">
          Home
        </NuxtLink>
      </div>
      <div>
        <NuxtLink to="/team" class=" rounded-xl p-2 md:px-6  hover:shadow-lg transition-all delay-75 duration-300 text-lg">
          Team
        </NuxtLink>
      </div>
      <div class="mr-4">
        <NuxtLink to="/courses"
          class=" rounded-xl p-2 md:px-6 hover:shadow-lg transition-all delay-75 duration-300 text-lg">
          Courses
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { Menu, MenuButton, MenuItem, MenuItems } from '@headlessui/vue';
</script>
