<template>
  <div class="text-[#FFEFD3] flex justify-between flex-col">
    <Return class="absolute top-5 left-5"></Return>
    <h1 class="">Welcome to clicker cookie</h1>
    <h2>Your count : {{ clickCookie }}</h2>
    <clicker :URL="'/img/cookie.png'" @cliked="addCounter()"></clicker>
  </div>
</template>

<script setup>

const clickCookie = ref(0)

const addCounter = () => {
  clickCookie.value += 1
}

</script>