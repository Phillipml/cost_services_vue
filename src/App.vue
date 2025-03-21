<script setup>
import Contact from "./components/Contact.vue";
import Spreadsheet from "./components/Spreadsheet.vue";
import WhatsappButton from "./components/WppButton.vue";
</script>

<template>
  <div id="app" class="bg-darkPurple text-white">
    <div class="container py-5">
      <header class="text-center">
        <h1 class="display-4 mb-5">Planilha orçamentária de custos</h1>
      </header>
      <Contact />
      <Spreadsheet />
    </div>
    <WhatsappButton />
  </div>
</template>

<style>
.bg-darkPurple {
  background-color: #0a0029;
}
</style>
