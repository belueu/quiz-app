<script setup>
import { RouterView } from "vue-router"
import HomeVue from "./views/HomeView.vue"


</script>

<template>
  <div>
    <HomeVue />
  </div>
</template>

<style scoped>
.container {
  max-width: 1000px;
  margin: 0 auto;
}

header {
  margin-bottom: 10px;
  margin-top: 30px;
  display: flex;
  align-items: center;
}

header h1 {
  font-weight: bold;
  margin-right: 30px;
}

header input {
  border: none;
  background-color: rgba(128, 128, 128, 0.1);
  padding: 10px;
  border-radius: 5px;
}

.cards-container {
  display: flex;
  flex-wrap: wrap;
  margin-top: 40px;
}

</style>