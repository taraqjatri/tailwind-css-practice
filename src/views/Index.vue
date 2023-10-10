<script setup>
</script>

<template>
  <div class="space-y-4">
    <div class="flex items-center space-x-4">
      <div class="w-1/5 flex justify-end">
        <img class="w-28" src="../assets/images/logo.png" alt="">
      </div>
      <div class="w-3/5">
        <ul class="flex justify-end space-x-4">
          <li>
            <a class="border-2 border-b-gray-600 hover:border-gray-600 hover:bg-gray-900 hover:text-white rounded-xl p-2" href="#">Home</a>
          </li>
          <li>
            <a class="border-2 border-b-gray-600 hover:border-gray-600 hover:bg-gray-900 hover:text-white rounded-xl p-2" href="#">About</a>
          </li>
          <li>
            <a class="border-2 border-b-gray-600 hover:border-gray-600 hover:bg-gray-900 hover:text-white rounded-xl p-2" href="#">Blog</a>
          </li>
          <li>
            <a class="border-2 border-b-gray-600 hover:border-gray-600 hover:bg-gray-900 hover:text-white rounded-xl p-2" href="#">Contact</a>
          </li>
          <li>
            <a class="border-2 border-b-gray-600 hover:border-gray-600 hover:bg-gray-900 hover:text-white rounded-xl p-2" href="#">Feedback</a>
          </li>
        </ul>
      </div>
      <div class="w-1/5 flex justify-center">
        <input class="mr-2 border-2 border-gray-400 p-2 rounded-xl" type="text" placeholder="Search here...">
      </div>
    </div>

    <div class="bg-gray-100">
      <div class="grid lg:grid-cols-2 2xl:grid-cols-5">
        <div class="px-8 py-12 max-w-md mx-auto sm:max-w-xl lg:max-w-full lg:px-12 lg:py-24 xl:mr-0 2xl:col-span-2">
          <div class="xl:max-w-xl">
            <img class="h-10" src="../assets/images/logo.svg" alt="workcation">
            <img class="mt-6 rounded-lg shadow-xl sm:h-64 sm:w-full sm:object-cover object-center lg:hidden"
                 src="../assets/images/beach-work.jpg" alt="Women workcation on the beach">

            <h1 class="text-2xl font-bold text-gray-900 mt-6 sm:text-4xl lg:text-3xl xl:text-4xl">You can work from
              anywhere.
              <br class="hidden lg:inline">
              <span class="text-purple-400 font">Take advantage of it.</span></h1>
            <p class="mt-6 text-gray-600 sm:text-xl">
              The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections
              1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact
              original form.
            </p>n

            <div class="mt-4 sm:mt-6">
              <a class="px-4 py-2 bg-indigo-500 rounded-lg text-white shadow-lg uppercase tracking-wider text-sm font-semibold sm:text-base"
                 href="#">
                Book Your Escape
              </a>
            </div>
          </div>
        </div>

        <div class="hidden relative lg:block 2xl:col-span-3">
          <img class="absolute inset-0 w-full h-full object-cover object-center" src="../assets/images/beach-work.jpg"
               alt="Women workstation on the beach">
        </div>
      </div>
    </div>
  </div>
</template>
