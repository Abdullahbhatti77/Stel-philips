<template>
    <div class="py-20 w-[70%] mx-auto">
      <div class="mx-auto px-6 text-center">
        <ul
          role="list"
          class="mx-auto grid grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8"
        >
          <li v-for="person in people" :key="person.name" class="bg-sky-50 ">
            <img class="h-40 w-full object-cover" :src="person.imageUrl" alt />
            <div class="py-4 px-6">
              <h3
                class="h-20 mt-0 text-xl font-semibold leading-7 tracking-tight text-left text-trisec"
              >{{ person.name }}</h3>
              <p class="text-sm leading-6 text-gray-700 text-left">{{ person.role }}</p>
              <div class="w-full h-full flex">
                <button
                  type="button"
                  class="bg-blue-500 xxs:py-2 md:ju md:py-4 xxs:px-2 md:px-8 text-sm font-semibold mt-8 text-white shadow-sm hover:bg-primary focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-sky-600"
                >Find out more</button>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </template>
  
  <script setup>
  const people = [
    {
      name: "Communities we serve",
      role: "Short description excerpt here",
      imageUrl:
        new URL("../assets/svg/CardImage3.svg",import.meta.url).href,
      twitterUrl: "#",
      linkedinUrl: "#"
    },
    {
      name: "Our Projects",
      role: "Short description excerpt here",
      imageUrl:
      new URL("../assets/svg/CardImage4.svg",import.meta.url).href,
      twitterUrl: "#",
      linkedinUrl: "#"
    },
    {
      name: "Where we operate",
      role: "Short description excerpt here",
      imageUrl:
      new URL("../assets/svg/CardImage5.svg",import.meta.url).href,
      twitterUrl: "#",
      linkedinUrl: "#"
    }
    // More people...
  ];
  </script>