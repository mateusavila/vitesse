<template>
  <div class="inline-flex flex-wrap text-2xl font-300 cursor-default justify-center">
    <div class="flex flex-col children:mx-auto">
      <img class="w-18 h-18 inline-block" src="@/public/nuxt.png">
      <span class="text-green5 mt--2">Nuxt 3</span>
    </div>
    <div
      class="transition-all-500 transform hover:rotate-135 m-x-4 y-auto text-3xl gray4"
      i-carbon-add
    />
    <div class="flex flex-col children:mx-auto">
      <img class="w-18 h-18 inline-block" src="@/public/vite.png">
      <span class="text-purple5 mt--2">Vitesse</span>
    </div>
    <div class="w-full bg-black block color-white mx-auto my-10px rounded-10px">
      Conteúdo centralizado num box
    </div>
  </div>
</template>
