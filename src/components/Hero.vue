<script>
  export default{
    components: {
      name: "hero"
    }
  };
</script>

<template>

  <div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
        <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>

        <div>
          <div class="relative pt-6 px-4 sm:px-6 lg:px-8">
            <nav class="relative flex items-center justify-between sm:h-10 lg:justify-start" aria-label="Global">
              <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
                <div class="flex items-center justify-between w-full md:w-auto">
                  <a href="#">
                    <img alt="Workflow" class="h-10 w-auto sm:h-12" src="https://i.postimg.cc/T18RpD6F/captive-Logo.jpg">
                  </a>
                </div>
              </div>
            </nav>
          </div>
        </div>

        <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
          <div class="sm:text-center lg:text-left">
            <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
              <span class="block xl:inline">JTBD research to find hidden growth opportunities</span>
              <!-- <span class="block text-indigo-600 xl:inline"></span> -->
            </h1>
            <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
              Helping brands and product teams uncover new opportunities for growth through Jobs-to-be-Done (JTBD) research.
              Customer interviews turn into quantitative surveys which lead to hidden opportunities for growth.
              </p>
            <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
              <div class="rounded-md shadow">
                <a href="mailto:nick@berkeleyblvd?subject=I want to build a roadmap of market winning solutions!" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-gray-900 hover:bg-gray-700 md:py-4 md:text-lg md:px-10"> Work with Me</a>
              </div>
              <div class="mt-3 sm:mt-0 sm:ml-3">
                <a href="https://calendly.com/berekelyblvd-nick/berkeley-blvd-user-research-introductory-call" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-gray-700 bg-gray-100 hover:bg-gray-200 md:py-4 md:text-lg md:px-10"> Schedule 30 Minutes </a>
              </div>
            </div>
            <div class="sm:text-center lg:text-left pt-5">
              <p>
                <a href="https://medium.com/@wichertn">👋 Check out some articles I've written</a>
              </p>
            </div>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="https://i.postimg.cc/8P9zxwpQ/casey-horner-4r-DCa5h-Bl-Cs-unsplash.jpg" alt="">
    </div>
  </div>

</template>

<style scoped>

</style>