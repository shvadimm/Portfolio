<template class="bg-black">
  <div class="bg-black h-screen">
    <header class="absolute inset-x-0 top-0 z-50">
      <nav class="flex items-center justify-between p-6 lg:px-8" aria-label="Global">
        <div class="flex lg:flex-1">
          <a href="#" class="-m-1.5 p-1.5">
            <span class="sr-only">Company</span>
            <img src="https://i.ibb.co/6WjvC8B/8146f5db32acfbacf7b5bbfa3953063f-removebg-preview.png" alt=""
              class="h-8 w-auto">
          </a>
        </div>
        <div class="flex lg:hidden">
          <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-white"
            @click="mobileMenuOpen = true">
            <span class="sr-only">main menu icon </span>
            <img src="https://cdn2.iconfinder.com/data/icons/e-commerce-clean-ui-flat/32/menu-64.png" alt=""
              class="h-8 w-auto">
          </button>
        </div>
        <div class="hidden lg:flex lg:gap-x-12">
          <a v-for="item in navigation" :key="item.name" :href="item.href"
            class="text-sm font-semibold leading-6 text-white">{{ item.name }}</a>
        </div>
      </nav>
      <Dialog as="div" class="lg:hidden" @close="mobileMenuOpen = false" :open="mobileMenuOpen">
        <div class="fixed inset-0 z-50" />
        <DialogPanel
          class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-white-900/10">
          <div class="flex items-center justify-between">
            <a href="#" class="-m-1.5 p-1.5">
              <span class="sr-only">Company</span>
              <img src="https://i.ibb.co/6WjvC8B/8146f5db32acfbacf7b5bbfa3953063f-removebg-preview.png" alt=""
                class="h-8 w-auto">
            </a>
            <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = false">
              <span class="sr-only">Close menu</span>
              <xmarkicon aria-hidden="true" class="h-6 w-6"><img
                  src="https://cdn2.iconfinder.com/data/icons/4web-3/139/close-64.png" alt="" class="h-8 w-auto">
              </xmarkicon>
            </button>
          </div>
          <div class="mt-6 flow-root">
            <div class="-my-6 divide-y divide-gray-500/10">
              <div class="space-y-2 py-6">
                <a v-for="item in navigation" :key="item.name" :href="item.href"
                  class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">{{
              item.name }}</a>
              </div>
            </div>
          </div>
        </DialogPanel>
      </Dialog>
    </header>

    <div class="relative isolate px-6 pt-14 lg:px-8">
      <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80"
        aria-hidden="true">
        <div
          class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#D5E2BC] to-[#A6979C] opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
        </div>
      </div>
      <div class="py-24 sm:py-32">
        <div class="mx-auto grid max-w-10xl gap-x-8 gap-y-20 px-6 lg:px-8 xl:grid-cols-2">
    
          <div class="relative h-200 w-80 overflow-hidden">
  <img class="h-full w-full object-cover" src="https://i.ibb.co/JBNYhLp/myphoto.png" alt="myphoto" border="0"/>
  <div class="absolute bottom-0 w-full h-16 bg-gradient-to-t from-transparent to-white"></div>
  <div class="absolute bottom-0 w-full h-16 -mt-16 blur-lg"></div>
</div>


        
      <div role="list" class="grid gap-x-8 gap-y-12 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2">

      
<div class="max-w-2xl">
  <h2 id="typed-text" class="text-4xl font-bold tracking-tight text-white sm:text-4xl"></h2>
  <p class="mt-6 text-lg leading-8 text-white">En tant que passionné de développement, je suis à la recherche d'un poste d'alternant pour la formation MSc Expert en informatique et systèmes d'information en bac +5 chez EPSI à la rentrée d'octobre 2024, afin de contribuer au succès de mon projet.</p>
</div>
    
      </div>
    </div>
      </div>
      <div
        class="absolute inset-x-0 top-[calc(100%-13rem)] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[calc(100%-30rem)]"
        aria-hidden="true">
        <div
          class="relative left-[calc(50%+3rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 bg-gradient-to-tr from-[#A6979C] to-[#D3C0D2] opacity-100 sm:left-[calc(50%+36rem)] sm:w-[72.1875rem]"
          style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import Typed from 'typed.js';

const navigation = [
  { name: 'Accueille', href: '/' },
  { name: 'Mon parcours', href: '/monparcours' },
  { name: 'Contact', href: '#' },
]

const mobileMenuOpen = ref(false)

onMounted(() => {
  var typed = new Typed('#typed-text', {
    strings: ['Bienvenue dans mon portfolio'],
    typeSpeed: 50,
  });
})
</script>

<style>
  @keyframes blink {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0;
    }
  }
</style>

