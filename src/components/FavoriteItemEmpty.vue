<script setup lang="ts">
import placeholderImage from '/images/FavoritePlaceholderImage.png';
</script>

<template>
  <div class="flex flex-col w-full p-2 justify-center items-center">
    <div class="">
      <img :src="placeholderImage" />
    </div>
    <div class="py-10">
      <h1 class="text-[1.35rem] text-center leading-8 font-bold">
        Список избранного пуст
      </h1>
      <p class="text-lg text-center">
        Добавляйте изображения, нажимая на звездочки
      </p>
    </div>
  </div>
</template>
