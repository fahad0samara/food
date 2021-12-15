<template>
  <div class="flex items-center justify-between space-x-4">
    <div class="ml-11  md:flex items-center space-x-8">
      <img src="../assets/1.jpg" class=" h-40 object-cover" />
    </div>

<div  class="md:hidden">
<button @click="show=!show">

    <svg xmlns="http://www.w3.org/2000/svg" class="h-9 w-9 mr-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
</svg>
</button>

</div>

    <div class=" hidden md:flex justify-between space-x-8 items-center">
      <nav>
        <div class="items-center md:flex">
          <div class=" flex-col md:flex-row md:mx-6">
            <a
              class="
                my-1
                xl:text-3xl
                font-bold
                text-pink-500
                dark:text-gray-200
                hover:text-blue-500
                dark:hover:text-blue-400
                md:mx-4 md:my-0
              "
              href="#"
              >Home</a
            >
            <a
              class="
                my-1
               xl:text-3xl
                font-medium
                text-pink-500
                dark:text-gray-200
                hover:text-blue-500
                dark:hover:text-blue-400
                md:mx-4 md:my-0
              "
              href="#"
              >Shop</a
            >
            <a
              class="
                my-1
                xl:text-3xl
                font-medium
                text-pink-500
                dark:text-gray-200
                hover:text-blue-500
                dark:hover:text-blue-400
                md:mx-4 md:my-0
              "
              href="#"
              >Contact</a
            >
            <a
              class="
                my-1
                xl:text-3xl
                font-medium
                text-pink-500
                dark:text-gray-200
                hover:text-blue-500
                dark:hover:text-blue-400
                md:mx-4 md:my-0
              "
              href="#"
              >About</a
            >
          </div>

          <div >
            <a
              class="
                relative
                text-gray-700
                dark:text-gray-200
                hover:text-gray-600
                dark:hover:text-gray-300
              "
              href="#"
            >
              <svg
                class="xl:w-10 xl:h-10 md:w-6 md:h-6 md:ml-5 text-black font-bold"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M3 3H5L5.4 5M7 13H17L21 5H5.4M7 13L5.4 5M7 13L4.70711 15.2929C4.07714 15.9229 4.52331 17 5.41421 17H17M17 17C15.8954 17 15 17.8954 15 19C15 20.1046 15.8954 21 17 21C18.1046 21 19 20.1046 19 19C19 17.8954 18.1046 17 17 17ZM9 19C9 20.1046 8.10457 21 7 21C5.89543 21 5 20.1046 5 19C5 17.8954 5.89543 17 7 17C8.10457 17 9 17.8954 9 19Z"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="h-7 w-2"
                />
              </svg>

              <span
                class="
                  absolute
                  top-0
                  left-0
                  p-1
                  text-xs text-white
                  bg-pink-500
                  rounded-full
                "
              ></span>
            </a>
          </div>
        </div>
      </nav>

      <div>
        <div class="flex items-center py-2 -mx-1 md:mx-5">
          <a
            class="
              block
              w-1/2
              px-4
              py-2
              mx-1
              text-xl
              font-bold
              leading-5
              text-center text-white
              transition-colors
              duration-200
              transform
              bg-pink-500
              rounded-md
              hover:bg-blue-600
              md:mx-2 md:w-auto
            "
            href="#"
            >Login</a
          >
          <a
            class="
              block
              w-1/2
              px-3
              py-2
              mx-1
              text-xl
              font-bold
              leading-5
              text-center text-white
              transition-colors
              duration-200
              transform
              bg-blue-500
              rounded-md
              hover:bg-blue-600
              md:mx-0 md:w-auto
            "
            href="#"
            >Join free</a
          >
        </div>
      </div>
    </div>

  </div>
   
   <div v-show="show" class=" space-y-3 text-center md:hidden">
    <a href="" class="block bg-red-400 text-white  font-bold  rounded-full mx-24 hover:bg-black text-2xl">home</a>
    <a href="" class="block bg-red-400 text-white  font-bold  rounded-full mx-24 hover:bg-black text-2xl">about</a>
    <a href="" class="block bg-red-400 text-white  font-bold  rounded-full mx-24 hover:bg-black text-2xl">contant</a>
    <a href="" class="block bg-red-400 text-white  font-bold  rounded-full mx-24 hover:bg-black text-2xl">blog</a>
    </div>
</template>
<script setup>
import { ref } from 'vue';
const show=ref(false)
</script>


