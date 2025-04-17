<template>
  <IconSvg />
  <MudarTema />
  <HeaderNavbar />
  
  <main class="flex-shrink-0">
    <div class="container">
      <RouterView />
    </div>
  </main>

  <FooterBar />
</template>

<script setup lang="ts">
import { RouterView } from "vue-router";

import IconSvg from "./components/icons/IconSVG.vue";
import MudarTema from "./components/layouts/MudarTema.vue";
import HeaderNavbar from "./components/layouts/HeaderNavbar.vue";
import FooterBar from "./components/layouts/FooterBar.vue";
</script>
