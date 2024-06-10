<script setup>
  import NavBar from './components/NabBar.vue'
  import Text from './components/Text.vue'
  import Pic from './components/Pic.vue'
</script>

<template>
  <div>
    <div>
      <NavBar/>
    </div>
    <main>
      <Text/>
      <Pic/>
    </main>

  </div>
</template>

<style scoped>
main{
  margin-top: 3.5rem;
  display: flex;
  justify-content: space-between;
  align-items:center;
}
</style>
