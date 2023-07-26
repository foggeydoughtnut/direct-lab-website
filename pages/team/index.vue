<template>
  <div>
    <div class="flex justify-center mt-8">
      <div class="w-2/3 text-left">
        <h1 class="text-2xl font-semibold text-blue-500 md:mt-8 mt-4 md:text-center">DIRECT Lab Team</h1>

        <div class="">
          <h2 class="text-xl font-semibold text-left md:mt-8 mt-4">Leadership</h2>
          <p class="md:mt-8 mt-4">
            Dr. Mario founded the DIRECT lab in 2021 and currently has five Ph.D. students, eight Masters students,
            several undergraduate research assistants, and one high school intern. If you would like to join us, scroll to
            the bottom.
          </p>
          <img src="/team/MarioPic.png" class="md:mt-8 mt-4" />

          <h2 class="text-xl font-semibold text-left md:mt-16 mt-8">Meet the team</h2>
          <p class="md:mt-8 mt-4">
            We value diligent effort, with a healthy dose of fun. If you have an interest in our work, we will find a
            place for you to apply your knowledge and background.
          </p>
          <img src="/team/SubTest.jpg" class="md:mt-8 mt-4" />
        </div>

        <div> <!-- PHD -->
          <h2 class="text-xl font-semibold text-left md:my-16 my-8">PhD Students</h2>
          <div class="grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 lg:gap-8 md:gap-4 gap-8">
            <TeamMember image-src="/team/Christopher.jpg" name="Christopher Allred"
              bio="Christopher is Christopher, a delicate but complex individual. Much like a French omlette." />
            <TeamMember image-src="/team/Kirby.png" name="Ryan Anderson" bio="" />
            <TeamMember image-src="/team/TaylorA.jpg" name="Taylor Anderson"
              bio="Currently is the top of the leaderboard in the DIRECT Lab Super Smash Bros. Nuf sed." />
            <TeamMember image-src="/team/Yoshi.png" name="Ela Bohlourihajar" bio="" />
            <TeamMember image-src="/team/Robbie.jpg" name="Robbie Buck" bio="" />
            <TeamMember image-src="/team/picture_of_huzeyfe.jpg" name="Huzefe Kocab"
              bio="Huzeyfe Kocabas is interested in exploring swarm robotics that reduce the overall time of task completion. He is specializing in auction-based approaches." />
          </div>
        </div>

        <div> <!-- Masters -->
          <h2 class="text-xl font-semibold text-left md:my-16 my-8">Masters Students</h2>
          <div class="grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 lg:gap-8 md:gap-4 gap-8">
            <TeamMember image-src="/team/CaptainFalcon.png" name="Tayler Baker" bio="" />
            <TeamMember image-src="/team/Luigi.png" name="Brian Callister" bio="" />
            <TeamMember image-src="/team/MetaKnight.png" name="Trey Crowther" bio="" />
            <TeamMember image-src="/team/ToonLink.png" name="Colton Hill" bio="" />
            <TeamMember image-src="/team/Ganondorf_SSBU.png" name="Chad" bio="" />

          </div>
        </div>

        <div> <!-- Undergrads -->
          <h2 class="text-xl font-semibold text-left md:my-16 my-8">Undergraduate Students</h2>
          <div class="grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 lg:gap-8 md:gap-4 gap-8">

            <TeamMember image-src="/team/Ness.png" name="Johnathan Craig" bio="" />
            <TeamMember image-src="/team/Pac-Man.png" name="Braxton Geary" bio="" />
            <TeamMember image-src="/team/Pikachu.png" name="Madison Patch" bio="" />
            <TeamMember image-src="/team/Gabe.jpg" name="Gabe Tonks" bio="" />
          </div>
        </div>

        <div> <!-- Alumni -->
          <h2 class="text-xl font-semibold text-left md:my-16 my-8">Alumni</h2>
          <div class="grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 lg:gap-8 md:gap-4 gap-8">
            <TeamMember image-src="/team/Carter.jpg" name="Carter Bailey"
              bio="I enjoy being in the outdoors especially when I can be on my bike. You can sometimes find me in the lab working on code or robots. My research ranges from training machine learned models to creating path planners for specific purposes" />
              <TeamMember image-src="/team/JigglyPuff.png" name="Laurel Bingham" bio="" />
            <TeamMember image-src="/team/Lucario.png" name="Johnathan Kunz" bio="" />
          </div>
        </div>

      </div>
    </div>
    <div class="bg-gray-200 flex flex-col justify-center items-center h-full mt-16 md:py-16 py-8">
      <h1 class="text-xl font-semibold md:mb-8 mb-4">Join the team</h1>
      <div class="md:w-1/5 w-3/5 items-center justify-center">
        <img src="/team/drmariooo.png" class="object-fit" />
      </div>
      <p class="md:my-8 my-4 mb-4 md:p-0 px-8">Contact us to find your place in the DIRECT Lab! We look forward to meeting
        you.</p>
      <NuxtLink to="https://docs.google.com/forms/d/e/1FAIpQLSfG5fMxJ6ytRbY_9SFDApNlITH_t9Xdg5YJzTzWmTsFwx8iAA/viewform"
        class="p-2 px-16 border border-blue-500 bg-none hover:bg-blue-100 transition-all duration-300 delay-75 text-lg text-blue-500 rounded-lg text-center"
        target="_blank">
        Join Us
      </NuxtLink>
    </div>
  </div>
</template>
