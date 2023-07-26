
<template>
  <div>
    <img :src="getImageURL()" />
    <h2 class="text-xl text-blue-500 font-semibold text-center md:mt-4 mt-2">{{ name }}</h2>
    <p class="text-left" v-show="bio">{{ bio }}</p>
  </div>
</template>

<script setup lang="ts">
const props = defineProps<{
  imageSrc: string,
  name: string,
  bio: string,
}>();

const getImageURL = () => {
  return props.imageSrc;
}
</script>