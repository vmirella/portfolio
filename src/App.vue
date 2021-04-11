<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" class="mx-auto" /> -->
  <!-- <HelloWorld msg="Hello Vue 3.0 + Vite" /> -->
  <!-- <p class="bg-purple-500">Hola</p> -->
  <!-- This example requires Tailwind CSS v2.0+ -->
  <div>
    <div class="top-0 z-20 py-6 px-4 sm:px-6 md:w-full lg:px-8 bg-indigo-900 bg-opacity-5">
      <nav class="relative flex items-center justify-between sm:h-10 lg:justify-start" aria-label="Global">
        <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
          <div class="flex items-center justify-between w-full md:w-auto">
            <a href="#">
              <span class="sr-only">icono</span>
              <img class="h-12 w-auto sm:h-16" src="./assets/mi_logo.png">
            </a>
            <div class="-mr-2 flex items-center md:hidden">
              <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500" aria-expanded="false">
                <span class="sr-only">Open main menu</span>
                <!-- Heroicon name: outline/menu -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
              </button>
            </div>
          </div>
        </div>
        <div class="hidden md:block md:ml-10 md:pr-4 md:space-x-8">
          <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Inicio</a>
          <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Proyectos</a>
          <a class="btn btn-indigo border-2 border-indigo-600 text-gray-900 py-2 px-4 focus:outline-none rounded-full bg-opacity-100  hover:bg-indigo-600 hover:text-white" href="https://drive.google.com/file/d/11RTb3jgdFhcVxZdm0uWjMZrNBbYeTMt9/view" target="_blank">
            Descargar CV
          </a>
        </div>
      </nav>
    </div>
    <div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto bg-violeta-400">
      <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:py-28 xl:py-32">
        <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>

        <!--
          Mobile menu, show/hide based on menu open state.

          Entering: "duration-150 ease-out"
            From: "opacity-0 scale-95"
            To: "opacity-100 scale-100"
          Leaving: "duration-100 ease-in"
            From: "opacity-100 scale-100"
            To: "opacity-0 scale-95"
        -->
        <!-- opciones -->
        <div class="absolute top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden">
          <div class="rounded-lg shadow-md bg-white ring-1 ring-black ring-opacity-5 overflow-hidden">
            <div class="px-5 pt-4 flex items-center justify-between">
              <div>
                <!-- <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg" alt=""> -->
                <img src="./assets/mi_logo.png" alt="Virginia Contreras" class="h-8 w-auto">
              </div>
              <div class="-mr-2">
                <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                  <span class="sr-only">Close main menu</span>
                </button>
              </div>
            </div>
            <div class="px-2 pt-2 pb-3 space-y-1">
              <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50">Proyectos</a>
              <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50">Descargar CV</a>
            </div>
            <a href="#" class="block w-full px-5 py-3 text-center font-medium text-indigo-600 bg-gray-50 hover:bg-gray-100">
              Cerrar
            </a>
          </div>
        </div>

        <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
          <div class="sm:text-center lg:text-left">
            <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
              <span class="block xl">Virginia Contreras</span>
              <span class="block text-indigo-600 xl font-medium text-3xl mt-8 lg:text-5xl">Front-end Developer</span>
            </h1>
            <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
              "Buscando nuevos retos cada día".
            </p>
            <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
              <a href="https://www.linkedin.com/in/virginia-mirella-contreras-villafuerte-1ab416167/" target="_blank" class="text-white bg-indigo-500 rounded-md border-gray-900 px-2 mr-3" style="font-size: 2em;">
                <i class="fab fa-linkedin-in"></i>
              </a>
              <a href="https://github.com/vmirella" target="_blank" class="text-white bg-indigo-500 rounded-md border-gray-900 px-2 mr-3" style="font-size: 2em;">
                <i class="fab fa-github"></i>
              </a>
              <a href="mailto:virginiacontrerasvillafuerte@gmail.com" class="text-white bg-indigo-500 rounded-md border-gray-900 px-2" style="font-size: 2em;">
                <i class="fas fa-envelope"></i>
              </a>
            </div>
          </div>
        </main>
      </div>
    </div>

    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="../src/assets/Virginia_Contreras.jpg" alt="">
    </div>
    </div>

    <div class="pt-12 bg-white md:pt-36">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="lg:text-center">
          <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">
            Proyectos
          </p>
        </div>
      </div>
    </div>
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12 bg-white">
      <div class="grid gap-y-8 md:grid-cols-2 md:gap-x-8">
        <div>
          <dt>
            <p class="text-lg leading-6 font-medium text-gray-900">Marca Perú</p>
          </dt>
          <dd class="my-2 text-base text-gray-500">
            Proyecto realizado como demo para un e-commerce. Implemetado en Vue y Vuex, consumiendo web services propias hechas en PHP con base de datos MySQL.
          </dd>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Responsive</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Vuetify</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Vue</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Vuex</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Axios</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">PHP 5.6</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">MySQL</div>

          <div class="mt-3">
            <button class="btn rounded-md bg-indigo-500 hover:bg-indigo-600 py-2 px-3 text-white mr-3">Página web</button>
            <button class="btn rounded-md bg-indigo-500 hover:bg-indigo-600 py-2 px-3 text-white">Código</button>
          </div>
        </div>
        <div class="flex justify-center">
          <img src="../src/assets/shopping_cart.png" alt="">
        </div>
      </div>
      <div class="grid gap-y-8 mt-16 md:grid-cols-2 md:gap-x-8">
        <div>
          <dt>
            <p class="text-lg leading-6 font-medium text-gray-900">Burger Queen</p>
          </dt>
          <dd class="my-2 text-base text-gray-500">
            Proyecto para una cadena de restaurantes, es un sistema que permite tomar pedidos, como requerimiento de desarrollo se pidió que se visualize desde una tablet.
          </dd>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Responsive</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Materialize</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">React</div>

          <div class="mt-3">
            <button class="btn rounded-md bg-indigo-500 hover:bg-indigo-600 py-2 px-3 text-white mr-3">Página web</button>
            <button class="btn rounded-md bg-indigo-500 hover:bg-indigo-600 py-2 px-3 text-white">Código</button>
          </div>
        </div>
        <div class="flex justify-center">
          <img src="../src/assets/burger_queen.png" alt="">
        </div>
      </div>
      <div class="grid gap-y-8 mt-16 md:grid-cols-2 md:gap-x-8">
        <div>
          <dt>
            <p class="text-lg leading-6 font-medium text-gray-900">Generador de carnet</p>
          </dt>
          <dd class="my-2 text-base text-gray-500">
            Puedes generar un carnet de registro e imprimirlo en formato pdf.
          </dd>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">Bootstrap</div>
          <div class="bg-indigo-200 rounded-md py-1 px-2 inline-block mr-2 mb-2 text-sm">React</div>

          <div class="mt-3">
            <button class="btn rounded-md bg-indigo-500 hover:bg-indigo-600 py-2 px-3 text-white mr-3">Página web</button>
            <button class="btn rounded-md bg-indigo-500 hover:bg-indigo-600 py-2 px-3 text-white">Código</button>
          </div>
        </div>
        <div class="flex justify-center">
          <img src="../src/assets/generador_carnet.png" alt="">
        </div>
      </div>
      <div class="grid divide-y divide-gray-200">
        <div></div>
        <div class="grid gap-y-0 pt-4 md:grid-cols-2 md:gap-x-8">
          <div class="flex items-center text-gray-400">Virginia Contreras Villafuerte © 2021</div>
          <div class="flex justify-start items-center text-gray-400 md:justify-end">
            <a href="https://www.linkedin.com/in/virginia-mirella-contreras-villafuerte-1ab416167/" target="_blank" class="text-gray-400 mr-5" style="font-size: 1.5em;">
              <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="https://github.com/vmirella" target="_blank" class="text-gray-400 mr-5" style="font-size: 1.5em;">
              <i class="fab fa-github"></i>
            </a>
            <a href="mailto:virginiacontrerasvillafuerte@gmail.com" class="text-gray-400" style="font-size: 1.5em;">
              <i class="fas fa-envelope"></i>
            </a>
          </div>
        </div>
      </div>
      <div class="fixed bottom-8 right-4 bg-indigo-600 text-white rounded-full h-16 w-16 flex items-center justify-center border-4 border-light-indigo-600 border-opacity-25 hover:border-indigo-400" style="font-size: 1.5em;">
        <i class="fas fa-arrow-up"></i>
      </div>
    </div>
  </div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
