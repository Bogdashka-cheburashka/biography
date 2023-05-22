<template> 
    <button 
      class="px-4 py-2 text-gray-950 font-normal  rounded-lg  hover:text-blue-50 "
      :class="size == 'sm' ? 'px-5' : size == 'md' ? 'px-7 ' : size == 'lg' ? 'px-4 ' : undefined"
    >
    {{ label }}
    </button> 
  </template>
  
  <script>
    export default {
      name: 'CustomButton',
      props: ['size', 'label']
    }
  </script>