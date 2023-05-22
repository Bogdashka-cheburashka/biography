<template>
    <!-- Шапка -->
    <header class="bg-white py-0 fixed top-0 backdrop-blur-md bg-white/50 border-b w-full h-auto">
        <div id="header" class="container mx-auto px-4 sm:px-6 md:px-8">
            <div class="flex items-center justify-between flex-wrap md:flex-nowrap">
                <p class="text-2xl font-medium">Bogdan Platon</p>
                <div class="flex items-center justify-center gap-x-4 py-3">
                    <div class="relative font-semibold">
                        <button type="button" 
                        onclick="location.href='portfolio'"  class="text-grey-800 focus:outline-none py-2 px-4 rounded">Главная</button>
                        <button type="button" 
                        onclick="location.href='#home'" class="text-grey-800 focus:outline-none py-2 px-4 rounded">Мои навыки</button>
                        <button type="button" 
                        onclick="location.href='#portfolio2'" class="text-grey-800 focus:outline-none py-2 px-4 rounded">Портфолио</button>
                        <button type="button" 
                        onclick="location.href='#about'" class="text-grey-800 focus:outline-none py-2 px-4 rounded">Опыт работы</button>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <body>
        <section class="grid items-center grid-cols-1 md:grid-cols-2 pt-28 md:pt-0 md:h-screen md:overflow-hidden">
            <div class="order-2 md:order-1 mt-10 ml-0 md:ml-40">
                <p class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white">Привет,</p>
                <p class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white">Я Платон Богдан</p>
                <p class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400">
                    Всем привет, меня зовут Платон Богдан и я студент первого курса Альметьевского Политехнического Техникума. Совсем с недавнего времени
                    занимаюсь програмированием и уже подготовил свой первый проект, который вы видите.
                </p>
                <!-- Кнопка -->
                <div class="flex items-left justify-start gap-x-4 py-3">
                    <a
                        href="https://github.com/Bogdashka-cheburashka"
                        class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800"
                    >
                        Мои проекты
                        <svg class="w-5 h-5 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path
                                fill-rule="evenodd"
                                d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                clip-rule="evenodd"
                            ></path>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="rounded-md h-60 md:h-1/2 full overflow-hidden order-1 md:order-2">
                <img class="rounded-md h-60 md:h-full overflow-hidden order-1 md:order-2" src="./images/i1.jpg" alt="profile" />
            </div>
        </section>
<!-- Мои навыки  -->
        <section class="bg-white dark:bg-gray-900">
  <div id="home" class="py-8 px-4 mx-auto max-w-screen-xl sm:py-16 lg:px-6">
      <div class="max-w-screen-md mb-8 lg:mb-16">
          <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Меня зовут Богдан,</h2>
          <p class="text-gray-500 sm:text-xl dark:text-gray-400">И сейчас я расскажу вам о своих навыках</p>
      </div>
      <div class="space-y-8 md:grid md:grid-cols-2 lg:grid-cols-3 md:gap-12 md:space-y-0">
          <div>
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                  <svg class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 3a1 1 0 000 2v8a2 2 0 002 2h2.586l-1.293 1.293a1 1 0 101.414 1.414L10 15.414l2.293 2.293a1 1 0 001.414-1.414L12.414 15H15a2 2 0 002-2V5a1 1 0 100-2H3zm11.707 4.707a1 1 0 00-1.414-1.414L10 9.586 8.707 8.293a1 1 0 00-1.414 0l-2 2a1 1 0 101.414 1.414L8 10.414l1.293 1.293a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Css</h3>
              <p class="text-gray-500 dark:text-gray-400"> В CSS я могу написать стили для веб-страниц. Я могу изменять размеры и цвета элементов, задавать расположение элементов на странице и создавать анимации.</p>
          </div>
          <div>
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                  <svg class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z"></path></svg>
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">HTML</h3>
              <p class="text-gray-500 dark:text-gray-400">В HTML я умею создавать веб-страницы с помощью разметки.Я знаю основные теги и элементы, такие как заголовок страницы (head), содержимое страницы (body), абзацы (p), изображения (img) и ссылки (a).</p>
          </div>
          <div>
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                  <svg class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z" clip-rule="evenodd"></path><path d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z"></path></svg>                    
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Vue</h3>
              <p class="text-gray-500 dark:text-gray-400"> В Vue я умею создавать компоненты на основе шаблонов и определения свойств через теги.Я знаком с основными элементами Vue, такими как директивы (v-if, v-for), вычисляемые свойства (computed) и методы (methods).</p>
          </div>
          <div>
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                  <svg class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M7 3a1 1 0 000 2h6a1 1 0 100-2H7zM4 7a1 1 0 011-1h10a1 1 0 110 2H5a1 1 0 01-1-1zM2 11a2 2 0 012-2h12a2 2 0 012 2v4a2 2 0 01-2 2H4a2 2 0 01-2-2v-4z"></path></svg>
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">JavaScript</h3>
              <p class="text-gray-500 dark:text-gray-400">В JavaScript я имею начальные навыки написания скриптов для взаимодействия со страницей и обработки данных. Я знаком с основными конструкциями языка, такими как циклы, условные операторы, функции и массивы.</p>
          </div>
      </div>
  </div>
</section>

        <div class="hidden md:flex items-center justify-between gap-3 w-full">
            <div class="bg-black/60 h-3 w-4"></div>
            <div class="bg-black/60 h-3 w-4"></div>
            <div class="bg-black/60 h-3 w-4"></div>
            <div class="bg-black/60 h-3 w-4"></div>
            <div class="bg-black/60 h-3 w-4"></div>
            <div class="bg-black/60 h-3 w-4"></div>
            <div class="bg-black/60 h-3 w-4"></div>
            <div id="portfolio2" class="bg-gradient-to-r from-black/60 to-black/0 flex-grow h-3"></div>
        </div>

        <section class="pt-32">
            <p class="text-4xl md:text-5xl text-center text-primary font-bold mb-8 md:mb-12">Потрфолио</p>
            <ul class="w-full md:w-5/6 space-y-10 py-5">
                <li class="flex flex-col md:flex-row items-center rounded overflow-hidden">
                    <div class="w-full md:w-1/3 h-60">
                        <img class="h-full w-full object-cover" src="./images/project.jpg" alt="portfolio" />
                    </div>
                    <div class="w-full md:w-2/3 p-5">
                        <h2 class="text-4xl font-semibold">Проект номер один</h2>
                        <p>Моим первым проектом стал сайт биографии обо мне.<br>Я выбрал его потому-что, это отличное начинание для тех, 
                            кто хочет изучить основы HTML и CSS, а также создать свой первый сайт.<br>
                            Создание сайта биографии помогло мне не только получить базовые знания веб-разработки, <br> 
                            но и развить свои творческие и организационные навыки, <br> 
                            что позволит мне создавать более сложные проекты в будущем.<br> </p>
                        <!-- Кнопка -->
                        <div class="flex items-left justify-start gap-x-4 py-3">
                            <a
                                href="https://github.com/Bogdashka-cheburashka"
                                class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800"
                            >
                                Мои проекты
                                <svg class="w-5 h-5 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        fill-rule="evenodd"
                                        d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                        clip-rule="evenodd"
                                    ></path>
                                </svg>
                            </a>
                        </div>
                    </div>
                </li>
            </ul>
        </section>
        <section class="py-40">
            <div id="about" class="flex flex-col md:flex-row items-center justify-center gap-10 md:gap-20">
                <div class="container mx-auto my-10">
                    <ExperienceSector
                        title="Мой опыт в программировании"
                        description="За короткий период изучения Vue, CSS и HTML на начальном уровне, я научился ставить цели и достигать их благодаря твёрдой уверенности и настойчивости в достижении своих целей. Полученные знания помогли мне создать веб-приложения с использованием Vue.js, а также структурировать и оформить веб-страницы с помощью CSS и HTML. Я научился проектировать и разрабатывать интерактивные пользовательские интерфейсы, используя Vue компоненты и Vue-Router, а также применять созданные стили CSS для того, чтобы сделать веб-сайт более привлекательным для пользователей. "
                        experience="Я имею опыт работы с такими технологиями, как JavaScript, Vue.Js, HTML и CSS."
                        image="./images/project.jpg"
                    />
                </div>
            </div>
        </section>
    </body>

    <footer class="p-4 bg-white sm:p-6 dark:bg-gray-800">
        <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
        <div class="sm:flex sm:items-center sm:justify-between">
            <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2023 <a href="https://vk.com/id267133394" class="hover:underline">Bogdan Platon™</a>.Все права защищены.
            </span>
            <div class="flex mt-4 space-x-6 sm:justify-center sm:mt-0">
                <a href="https://github.com/Bogdashka-cheburashka" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
                    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" /></svg>
                </a>
                <a href="https://vk.com/id267133394" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
                    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z" clip-rule="evenodd" /></svg>
                </a>
            </div>
        </div>
</footer>
</template>

<script>
import { initFlowbite } from "flowbite";
import ExperienceSector from "./ExperienceSector.vue";

export default {
    name: "App",
    components: {
        ExperienceSector,
    },
    data() {
        return {};
    },
    mounted() {
        initFlowbite();
    },
};
</script>
