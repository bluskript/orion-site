<template>
  <div class="hero relative bg-dark-800 z-0">
    <div id="bg" class="-z-1 absolute w-full h-full" />
    <div class="px-24 md:px-48 py-32 w-full transform translate-y-24">
      <div class="z-2 flex flex-col align-middle">
        <h1 class="text-6xl font-bold mb-4">
          We are Team Orion.
        </h1>
        <p class="mb-4 text-gray-300 text-xl">
          A US-based RoboCup Junior team
        </p>
        <div class="flex gap-4">
          <HBtn class="docs-btn">
            Robocup 2021 case study
            <mdi-chevron-right />
          </HBtn>
          <HBtn class="docs-btn">
            About us
            <mdi-chevron-right />
          </HBtn>
        </div>
      </div>
    </div>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path class="fill-dark-800" fill-opacity="1" d="M0,64L60,85.3C120,107,240,149,360,154.7C480,160,600,128,720,138.7C840,149,960,203,1080,234.7C1200,267,1320,277,1380,282.7L1440,288L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path>
    </svg>
  </div>
</template>

<style lang="postcss" scoped>
.hero {
  @apply bg-dark-900;
  background-image: url('/assets/svg/eyes.svg');
}

.docs-btn {
  @apply gap-2;

  svg {
    @apply transition-transform duration-200;
  }

  &:hover svg {
    @apply transform translate-x-1;
  }
}
</style>
