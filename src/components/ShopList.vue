<template>
  <section class="py-16 md:py-24">
    <div class="mx-auto max-w-[1200px] px-4">
      <h2
        class="mb-10 text-center text-[42px] leading-none tracking-wide text-[#7a6554] md:mb-14 md:text-[56px]"
      >
        SHOPLIST
      </h2>
      <div
        class="mx-auto grid max-w-[800px] grid-cols-2 gap-7 md:grid-cols-3 md:gap-x-7 md:gap-y-10"
      >
        <div
          v-for="shop in shops"
          :key="shop.name"
          class="group relative overflow-hidden rounded-[10px]"
        >
          <img
            :src="shop.image"
            :alt="shop.name"
            class="h-[260px] w-full object-cover md:h-[320px]"
          />
          <!-- ホバー時の白フィルター -->
          <div
            class="absolute inset-0 z-10 rounded-[10px] bg-white/0 transition duration-300 group-hover:bg-white/30"
          ></div>
          <div
            class="absolute bottom-0 left-0 z-20 flex w-full items-center justify-between bg-[#7a6554]/55 px-4 py-3 text-white transition duration-300 group-hover:bg-white/60"
          >
            <span
              class="text-sm font-bold transition duration-300 group-hover:text-[#7a6554] md:text-[16px]"
            >
              {{ shop.name }}
            </span>

            <span
              class="flex h-6 w-6 items-center justify-center rounded-full border border-white text-xs group-hover:border-[#7a6554] group-hover:text-[#7a6554]"
            >
              →
            </span>
          </div>
        </div>
      </div>
      <div class="mt-10 flex justify-center md:mt-12">
        <button
          class="flex items-center justify-center gap-6 rounded-full bg-[#7a6554] px-8 py-4 text-sm font-bold text-white transition hover:opacity-90 md:min-w-[260px]"
        >
          行きたいお店を探す
        </button>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
const shops = [
  {
    name: "関東",
    image: new URL("../assets/img/shop1.jpg", import.meta.url).href,
  },
  {
    name: "中部",
    image: new URL("../assets/img/shop2.jpg", import.meta.url).href,
  },
  {
    name: "近畿",
    image: new URL("../assets/img/shop3.jpg", import.meta.url).href,
  },
  {
    name: "中国・四国",
    image: new URL("../assets/img/shop4.jpeg", import.meta.url).href,
  },
  {
    name: "九州",
    image: new URL("../assets/img/shop5.jpg", import.meta.url).href,
  },
  {
    name: "海外",
    image: new URL("../assets/img/shop6.jpg", import.meta.url).href,
  },
];
</script>
