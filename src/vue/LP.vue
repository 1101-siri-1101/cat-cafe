<template>
  <div class="relative">
    <section class="relative h-screen">
      <div
        class="absolute top-0 left-0 z-80 flex w-full items-center justify-between px-[50px] md:px-[100px] py-[30px]"
        :class="[
          isOpenMenu ? 'fixed bg-white' : '',
          isScrolled && !isOpenMenu
            ? 'fixed top-0 left-0 bg-white transition-all duration-500 translate-y-0 opacity-100'
            : '',
        ]"
      >
        <img
          src="../assets/img/logo.png"
          alt="logo"
          class="h-[60px] md:h-[90px]"
        />
        <button
          class="rounded-full border-none flex h-[70px] w-[70px] cursor-pointer items-center justify-center bg-[#756659] font-bold text-white text-4xl md:h-[100px] md:w-[100px]"
          :class="{ 'md:text-sm text-[11px]': !isOpenMenu }"
          @click="switchDisplayMenu"
        >
          {{ menuText }}
        </button>
      </div>

      <Movie />
    </section>

    <Menu v-if="isOpenMenu" />
    <Concept />
    <Info />

    <Footer />
  </div>
</template>

<script setup lang="ts">
import Menu from "../components/menu.vue";
import { computed } from "vue";
import Movie from "../components/Movie.vue";
import Concept from "../components/Concept.vue";
import Footer from "../components/Footer.vue";

import { ref, onMounted, onBeforeUnmount } from "vue";
import Info from "../components/info.vue";

const isScrolled = ref(false);
const isOpenMenu = ref<boolean>(false);

function switchDisplayMenu() {
  isOpenMenu.value = !isOpenMenu.value;
}

const menuText = computed(() => {
  return isOpenMenu.value ? "×" : "MENU";
});

const handleScroll = () => {
  isScrolled.value = window.scrollY > window.innerHeight * 0.8;
};

onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

onBeforeUnmount(() => {
  window.removeEventListener("scroll", handleScroll);
});
</script>
