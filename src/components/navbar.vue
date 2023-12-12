<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <nav class="bg-white">
      <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="relative flex h-16 items-center justify-between">
          <div class="flex flex-shrink-0 mt-2">
              <img class="h-14 w-auto" src="https://www.microprixs.com/wp-content/uploads/2021/01/Picture1.png" alt="Your Company">
            </div>
          <div class="absolute right-0 flex items-center sm:hidden hover:bg-white">
            <!-- Mobile menu button-->
            <button type="button" class="relative inline-flex  rounded-md p-2 text-gray-400 " aria-controls="mobile-menu" aria-expanded="false"  v-on:click="toggleNavbar1()">
              <!-- <span class="sr-only">Open main menu</span> -->
             
              <svg class="block h-10 w-10" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
              </svg>
              
              <svg class="hidden h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
              </svg>
            </button>
          </div>
          <div class="flex flex-1 items-end justify-end sm:items-stretch sm:justify-start">
            
            <div class="hidden sm:ml-6 sm:block">
              <div class="flex space-x-4">
              <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
              <router-link to="/" class="text-gray-300 hover:bg-gray-700 rounded-md px-3 py-2 text-sm font-medium" aria-current="page">Dashboard</router-link>
              <router-link to="/about" class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium">About</router-link>
              <router-link to="/team" class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium">Team</router-link>
              <router-link to="/contact" class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium">Contact</router-link>
            </div>
            <RouterView></RouterView>
            </div>
          </div>
          
    </div>  
    </div>
    
    
      <div class="sm:hidden" id="mobile-menu" v-bind:class="{'hidden': !shownav, 'flex': shownav}">
        <div class="space-y-1 px-2 pb-3 pt-2">
          <router-link to="/" class="text-gray-300 hover:bg-gray-700 block rounded-md px-3 py-2 text-base font-medium" aria-current="page">Dashboard</router-link>
          <router-link to="/about" class="text-gray-300 hover:bg-gray-700 hover:text-white :bg-gray-900 block rounded-md px-3 py-2 text-base font-medium">About</router-link>
          <router-link to="/team" class="text-gray-300 hover:bg-gray-700 hover:text-white block rounded-md px-3 py-2 text-base font-medium">Team</router-link>
          <router-link to="/contact" class="text-gray-300 hover:bg-gray-700 hover:text-white block rounded-md px-3 py-2 text-base font-medium">Contact</router-link>
        </div>
      </div>
    </nav>
    </template>
    
    
    <script>
      export default {
      name: "pink-navbar",
      data() {
      return {
      showMenu: false,
      shownav:false,
      }
      },
      methods: {
      toggleNavbar: function(){
      this.showMenu = !this.showMenu;
     } ,
     toggleNavbar1: function(){
      this.shownav = !this.shownav;
     } 
     }
     }
    </script>
    