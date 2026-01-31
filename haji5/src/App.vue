<template>
    <header>
      <Logo></Logo>
    </header>
    <main>
      <SectionOne />
      <SectionTwo />
      <SectionThree />
    </main>
</template>

<script setup lang="ts">
import Logo from "./components/Logo.vue"
import SectionOne from './components/SectionOne.vue'
import SectionTwo from './components/SectionTwo.vue'
import SectionThree from './components/SectionThree.vue'
</script>

<style scoped>
header {
  width: 100%;
}
header h1 {
  font-size: 2.5rem;
  margin-bottom: 40px;
  color: #333;
}
main {
  overflow-y: scroll; 
  width: 100%;
  height: 100%;
  gap: 40px;
}
</style>
