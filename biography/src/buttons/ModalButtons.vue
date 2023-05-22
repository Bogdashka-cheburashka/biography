<!-- Выезжающая кнопка  -->
<div class="relative inline-flex">
    <button class="px-2 py-3 text-sm font-medium bg-gray-800 text-gray-200 rounded-md shadow-sm block">Наведи на меня</button>
    <div class="absolute z-10 hidden mt-2 py-2 w-40 bg-white rounded-lg shadow-lg">
      <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-indigo-500 hover:text-white">Кнопка 1</a>
      <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-indigo-500 hover:text-white">Кнопка 2</a>
      <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-indigo-500 hover:text-white">Кнопка 3</a>
    </div>
  </div>

<!-- <script> 
$(document).ready(function () {
  $('.relative').hover(function () {
    $(this).children('.absolute').toggleClass('hidden');
  });
});
</script>-->