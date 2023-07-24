<template>
  <div class="flex justify-center mt-8">
    <div class="w-2/3 md:text-center text-left">
      <h1 class="md:text-5xl text-3xl font-semibold text-blue-500 md:mt-8 mt-4">Robotics</h1>

      <div class="grid lg:grid-cols-4 md:grid-cols-2 grid-cols-1 md:gap-8 gap-2 mt-16">
        <div>
          <img src="/Bio-Inspired.jpg" />
          <p class="md:mt-4 mt-2 text-lg">Bio-Inspired Robotics</p>
          <p class="md:mt-8 mt-2 text-lg">Legged Vehicles</p>
        </div>
        <div>
          <img src="/UGV.jpg" class="mt-8 md:mt-0" />
          <p class="md:mt-4 mt-2 text-lg">UGV</p>
          <p class="md:mt-8 mt-2 text-lg">Unmanned Ground Vehicles</p>
        </div>
        <div>
          <img src="/AUV.jpg" class="mt-8 md:mt-0" />
          <p class="md:mt-4 mt-2 text-lg">AUV</p>
          <p class="md:mt-8 mt-2 text-lg">Autonomous Underwater Vehicle</p>
        </div>
        <div>
          <img src="/UAV.jpg" class="mt-8 md:mt-0" />
          <p class="md:mt-4 mt-2 text-lg">UAV</p>
          <p class="md:mt-8 mt-2 text-lg">Unmanned Aerial Vehicles</p>
        </div>

      </div>


      <div class="grid md:grid-cols-2 grid-cols-1 md:gap-8 gap-2 mt-16">
        <img src="/Terrain-Adaptive.jpg" />
        <div>
          <h1 class="text-2xl font-semibold text-left text-blue-500 md:mt-4 mt-0">Terrain Adaptive Intelligence</h1>
          <p class="text-left md:mt-8 mt-2">Humans naturally stiffen or loosen their legs while walking on different
            terrains to maintain a stable walk or run. Further, we (as humans) are aware after just a few steps how a
            surface might impact the way we move: we show down when it's slippery; we turn less sharply; and we favor some
            surfaces (concrete) over others (deep snow). This research builds intelligence frameworks that quickly
            identify terrains, adapt robot motion, and build new plans for navigation based on activity learned
            information.</p>
        </div>

        <div>
          <!-- Only shows when the screen in on mobile -->
          <img src="/Vegetation-Traversal.jpg" class="mt-16 md:mt-0 md:hidden block" />
          <h1 class="text-2xl font-semibold text-left text-blue-500 md:mt-4 mt-0">Vegetation Traversal
          </h1>
          <p class="text-left md:mt-8 mt-2">Robots have a hard time differentiating obstacles that are real and obstacles
            that are not. A bladder of grass can seem in. This research builds frameworks that help robots learn to
            distinguish between plans that are navigable from those which are real obstacles. Further, our robots learn
            the expected cost of such an operation; this is often in terms of energy and stability.</p>
        </div>
        <!-- Only shows when the screen in on desktop -->
        <img src="/Vegetation-Traversal.jpg" class="mt-16 md:mt-0 md:block hidden" />

        <img src="/Placeholder-Image.png" class="mt-16 md:mt-0" />
        <div>
          <h1 class="text-2xl font-semibold text-left text-blue-500 md:mt-4 mt-0">Stealth Aware
          </h1>
          <p class="text-left md:mt-8 mt-2">Many animals and insects do not move in open, flat regions, but naturally find
            ways to navigate the environments while minimizing line of sight with any potential predators. This research
            builds a bio-inspired, stealthy planner that guides robots to navigate similar to their biological
            counterparts.</p>
        </div>

        <div>
          <img src="/Placeholder-Image.png" class="mt-16 md:mt-0 md:hidden block" />
          <h1 class="text-2xl font-semibold text-left text-blue-500 md:mt-4 mt-0">Human Trajectory
          </h1>
          <p class="text-left md:mt-8 mt-2">Human-rich enchants are difficult for robots to work in largely due to the
            inability to understand, predict, and plan based on human objectives. Robots, frankly, have no idea what
            humans are going to do. This research predicts human actions and builds belief spaces around their expected
            futures.
            counterparts.</p>
        </div>
        <img src="/Placeholder-Image.png" class="mt-16 md:mt-0 md:block hidden" />

        <img src="/Prosthetic.jpg" class="mt-16 md:mt-0" />
        <div>
          <h1 class="text-2xl font-semibold text-left text-blue-500 md:mt-4 mt-0">Prosthetic
          </h1>
          <p class="text-left md:mt-8 mt-2">Simple 3D printed robotic hands have the potential to help many people
            experiment with and try robotic prosthetics. We have several designs and types being tested.</p>
        </div>

        <img src="/Placeholder-Image.png" class="mt-16 md:mt-0 md:hidden block" />
        <div>
          <h1 class="text-2xl font-semibold text-left text-blue-500 md:mt-4 mt-0">Multi-drone Search
          </h1>
          <p class="text-left md:mt-8 mt-2">Leveraging many small-scale systems can cover large amounts of space quickly,
            but systems have to self-organize or be directed in order to effectively solve collaborative tasks. Our
            objectives are to use human-like strategies to incentivize actions without needing direct control.</p>
        </div>
        <img src="/Placeholder-Image.png" class="mt-16 md:mt-0 md:block hidden" />
      </div>


    </div>
  </div>
</template>