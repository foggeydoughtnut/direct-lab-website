<template>
  <div>
    <div class="md:h-[60vh] h-[35vh] relative w-screen">
      <img src="/Spot-Zombie.jpg" class="h-full w-full object-cover absolute brightness-50" />
      <img src="/DIRECT Lab Logo-A.png" class="object-scale-down absolute md:top-0 top-4 w-full" />
      <h1 class=" text-white text-xl lg:text-3xl font-semibold absolute md:bottom-20 bottom-10 text-center w-full">
        Decision Intelligence, Robotics, and Electrified Transportation Lab</h1>
    </div>

    <div class="flex justify-center mt-8">
      <div class="w-2/3 md:text-center text-left">
        <h1 class="text-2xl font-semibold text-blue-500 md:mt-8 mt-4">Mission and Purpose</h1>
        <p class="md:mt-8 mt-4">DIRECT Lab strives to improve quality of life by developing intelligent systems capable of
          assisting humans operating in a complex and uncertain world.</p>


        <!-- Carousel -->
        <div class="md:my-16 my-4">
          <Carousel :autoplay="4000" :wrap-around="true">
            <Slide v-for="image in carouselImages" :key="image">
              <div class="carousel__item flex items-center justify-center w-full h-full">
                <img :src=image class="object-cover w-full h-full" />
              </div>
            </Slide>
          </Carousel>
        </div>

        <h1 class="text-2xl font-semibold text-blue-500 md:mt-16 mt-8">About the Lab</h1>
        <p class="md:mt-8 mt-4">
          USU’s DIRECT lab covers three categories of research: Decision Intelligence, Robotics, and Electrified
          Transportation. Founded by Dr. Mario, the lab strives to expand and unite research in applied AI, especially for
          electrified transportation and autonomous systems. Almost everything we do, we build software: we apply decision
          intelligence and software development to the other fields. Current research is applied in financial markets,
          power electronics, transportation infrastructure, human behavior, and robotics. The DIRECT lab also focuses on
          outreach and providing opportunities for underserved communities to participate in research.
        </p>

        <div class="grid lg:grid-cols-4 md:grid-cols-2 grid-cols-1 md:gap-8 gap-2 mt-16">
          <NuxtLink to="/decision-intelligence">
            <img src="/Decision-Int-Picture.jpg" />
          </NuxtLink>
          <div class="flex flex-col">
            <NuxtLink to="/decision-intelligence" class="text-2xl font-semibold text-blue-500 text-start underline">
              Decision Intelligence</NuxtLink>
            <p class="text-left md:mt-8 mt-2">Understanding principles that allow human-like decision making in uncertain
              environments with limited information </p>
          </div>

          <NuxtLink to="/robotics">
            <img src="/Spot.jpg" class="mt-16 md:mt-0" />
          </NuxtLink>
          <div class="flex flex-col">
            <NuxtLink to="/robotics" class="text-2xl font-semibold text-blue-500 text-start underline">Robotics</NuxtLink>
            <p class="text-left md:mt-8 mt-2">Design of intelligence hierarchy and architectures to quickly learn and
              adapt on all types of robots</p>
          </div>

          <NuxtLink to="/electrified-transportation">
            <img src="/Electrified-Transportation.png" class="mt-16 md:mt-0" />
          </NuxtLink>
          <div class="flex flex-col">
            <NuxtLink to="/electrified-transportation" class="text-2xl font-semibold text-start text-blue-500 underline">
              Electrified Transportation</NuxtLink>
            <p class="text-left md:mt-8 mt-2">Intelligent clean energy autonomy for transportation, cities, and
              infrastructure</p>
          </div>

          <NuxtLink to="/outreach">
            <img src="/spot-outreach.png" class="mt-16 md:mt-0" />
          </NuxtLink>
          <div class="flex flex-col">
            <NuxtLink to="/outreach" class="text-2xl font-semibold text-start text-blue-500 underline">Outreach</NuxtLink>
            <p class="text-left md:mt-8 mt-2">Building ties to communities and future researchers</p>
          </div>
        </div>


        <div class="flex justify-center">
          <div class="md:w-1/2">
            <h1 class="text-2xl mt-16 text-blue-500 font-semibold">Questions?</h1>
            <p class="md:mt-8 my-2 mb-8">Visit SER 140 or use the Form below for more information or to tour the lab.</p>

            <NuxtLink
              to="https://docs.google.com/forms/d/e/1FAIpQLSfAX4iZq1ByAlNWtE0D37OVTnP5bRa7xBrjjy5CZY_AwRbycw/viewform"
              class="w-full p-2 px-16 border border-blue-500 bg-none hover:bg-blue-100 transition-all duration-300 delay-75 text-lg text-blue-500 rounded-lg"
              target="_blank">
              Contact Us
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
  const carouselImages = [
    'tank.jpg',
    'AUV-Carousel.jpg',
    'UAV-Carousel.jpg',
    'Bio-Inspired.jpg'
  ]
</script>


<style>
  .carousel__slide {
    height: 40vh;
  }
</style>
