<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      <a href="" target="" rel="noopener">Contact: <br> +6281364103405</a><br>
      <a href="https://api.whatsapp.com/send/?phone=%2B6281364103405&text&type=phone_number&app_absent=0" target="_blank" rel="noopener">081364103405</a> <br>
      <a href="https://www.instagram.com/naufalaulia_?igsh=NDF5cXltbzc2ZHVz" target="_blank" rel="noopener">naufalaulia_</a><br>
      <a href="https://mail.google.com/mail/u/0/#inbox" target="_blank" rel="noopener">naufalaulia140704@gmail.com</a><br>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>