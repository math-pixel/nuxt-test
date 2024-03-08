<template>
  <div>
    <Return></Return>
    <h1 class="bg-red-500">Welcome to clicker cookie</h1>
    <h2>your count : {{ clickCookie }}</h2>
    <clicker :URL="'/img/cookie.png'" @cliked="addCounter()"></clicker>
  </div>
</template>

<script setup>

const clickCookie = ref(0)

const addCounter = () => {
  clickCookie.value += 1
}

</script>