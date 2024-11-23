<script setup>
// import { GlobeAsiaAustraliaIcon } from '@heroicons/vue/24/outline'
</script>

<template>
<!-- <GlobeAsiaAustraliaIcon class="size-6 ml-2" /> -->

  <div class="px-8 py-6 border-b-[1px] border-slate-300 ">
    <div class="flex-col">
      <div class="text-3xl font-bold text-sky-500">
        <h1>DESIGN SYSTEM</h1>
      </div>
      <div class="text-xl text-slate-500">
        <h4>VUE & TAILWIND TRAINING</h4>
      </div>
    </div>
  </div>

  <div class="grid grid-cols-none lg:grid-flow-col-dense">
    
    <div class="px-6 py-3 border-slate-300 h-max-content border-b-[1px] lg:px-6 lg:py-6 lg:border-r-[1px] lg:border-b-0">
      <div class="flex flex-col">
        <a href="#" class="snav-link">Foundations</a>
        <a href="#" class="snav-link">Input Fields</a>
        <a href="#" class="snav-link">Dropdowns</a>
        <a href="#" class="snav-link">Buttons</a>
      </div>
    </div> 
    <!-- end sidenav -->

    <div class="px-8 py-6 w-full lg:px-16 lg:py-12">
      <div class="text-2xl font-bold text-slate-700 mb-5">
        <h3>Typography</h3>
      </div>
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
        <div class="border-[1px] rounded p-6 grid lg:grid-rows-2">
          <p class="page-title">
            The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog.
          </p>
          <div class="grid grid-rows-3">
            <hr class="my-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                  Palette Name
                </div>
                page-title
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Typeface
                </div>
                Nunito
              </div>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                Tailwind Class
                </div>
                text-2xl
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Font Weight
                </div>
                Bold
              </div>
            </div>
          </div>
        </div>
        <div class="border-[1px] rounded p-6 grid lg:grid-rows-2">
          <p class="page-subtitle">
            The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog.
          </p>
          <div class="grid grid-rows-3">
            <hr class="my-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                  Palette Name
                </div>
                page-subtitle
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Typeface
                </div>
                Nunito
              </div>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                Tailwind Class
                </div>
                text-xl
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Font Weight
                </div>
                Normal
              </div>
            </div>
          </div>
        </div>
        <div class="border-[1px] rounded p-6 grid lg:grid-rows-2">
          <p class="page-text">
            The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog.
          </p>
          <div class="grid grid-rows-3">
            <hr class="my-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                  Palette Name
                </div>
                page-text
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Typeface
                </div>
                Nunito
              </div>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                Tailwind Class
                </div>
                text-base
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Font Weight
                </div>
                Normal
              </div>
            </div>
          </div>
        </div>
        <div class="border-[1px] rounded p-6 grid lg:grid-rows-2">
          <p class="page-subtext">
            The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog.
          </p>
          <div class="grid grid-rows-3">
            <hr class="my-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                  Palette Name
                </div>
                page-subtext
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Typeface
                </div>
                Nunito
              </div>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 lg:gap-4">
              <div class="flex">
                <div class="mr-auto font-bold">
                Tailwind Class
                </div>
                text-sm
              </div>
              <div class="flex">
                <div class="mr-auto font-bold">
                  Font Weight
                </div>
                Normal
              </div>
            </div>
          </div>
        </div>
      </div> <!-- end typography -->

      <div class="text-2xl font-bold text-slate-700 mb-5 mt-10">
        <h3>Colors</h3>
      </div>
      <div class="grid grid-cols-1 lg:grid-cols-9 grid-flow-row gap-6">
        <div class="col-span-1">
          <div class="text-xl font-bold text-slate-600">
            Slate
          </div>
        </div>
        <div class="col-span-8 grid grid-cols-3 lg:grid-cols-6 gap-5">
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-slate-50 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                50
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-slate-100 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                100
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-slate-300 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                300
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-slate-500 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                500
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-slate-700 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                700
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-slate-900 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                900
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-1">
          <div class="text-xl font-bold text-slate-600">
            Red
          </div>
        </div>
        <div class="col-span-8 grid grid-cols-3 lg:grid-cols-6 gap-5">
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-red-50 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                50
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-red-100 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                100
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-red-300 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                300
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-red-500 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                500
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-red-700 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                700
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-red-900 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                900
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>          
        </div>
        <div class="col-span-1">
          <div class="text-xl font-bold text-slate-600">
            Green
          </div>
        </div>
        <div class="col-span-8 grid grid-cols-3 lg:grid-cols-6 gap-5">
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-green-50 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                50
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-green-100 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                100
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-green-300 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                300
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-green-500 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                500
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-green-700 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                700
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-green-900 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                900
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-1">
          <div class="text-xl font-bold text-slate-600">
            Sky
          </div>
        </div>
        <div class="col-span-8 grid grid-cols-3 lg:grid-cols-6 gap-5">
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-sky-50 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                50
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-sky-100 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                100
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-sky-300 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                300
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-sky-500 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                500
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-sky-700 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                700
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-sky-900 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                900
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-1">
          <div class="text-xl font-bold text-slate-600">
            Pink
          </div>
        </div>
        <div class="col-span-8 grid grid-cols-3 lg:grid-cols-6 gap-5">
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-pink-50 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                50
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-pink-100 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                100
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-pink-300 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                300
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-pink-500 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                500
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-pink-700 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                700
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
          <div class="grid grid-rows-2 gap-2">
            <div class="w-full h-16 bg-pink-900 rounded-xl">
            </div>
            <div class="">
              <p class="text-lg font-bold text-slate-600">
                900
              </p>
              <p class="text-base text-slate-600">
                #000000
              </p>
            </div>
          </div>
        </div>
      </div> <!-- end colors -->

      <div class="text-2xl font-bold text-slate-700 mb-5 mt-10">
        <h3>Input fields</h3>
      </div>

    </div>  <!-- end right container -->

  </div>
  

</template>

<style scoped>

</style>
