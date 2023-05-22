<template>
    <div class="container mx-auto my-10">
      <div class="flex flex-wrap justify-center items-center py-5">
        <div class="w-full md:w-4/12">
          <img class="w-1/2 h-auto object-cover" :src="image" :alt="imageAlt" />
        </div>
        <div class="w-full md:w-8/12 px-5 text-center md:text-left">
          <h2 class="text-4xl font-bold text-gray-800 text-center md:text-left">{{ title }}</h2>
          <div class="text-lg text-gray-600 my-5">{{ description }}</div>
          <div class="text-sm text-gray-600">{{ experience }}</div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ExperienceSector',
    props: {
      title: {
        type: String,
        required: true
      },
      description: {
        type: String,
        required: true
      },
      experience: {
        type: String,
        required: true
      },
      image: {
        type: String,
        required: true
      }
    }
  }
  </script>