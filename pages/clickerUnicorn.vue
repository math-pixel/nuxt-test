<template>
  <div>
    <Return></Return>
    <h1>Welcome to clicker Unicorn</h1>
    <h2>your counter : {{ clickUnicorn }}</h2>
    <clicker :URL="'/img/licorne.png'" @cliked="addCounter()"></clicker>

  </div>
</template>

<script setup>

const clickUnicorn = ref(0)

const addCounter = () => {
  clickUnicorn.value += 1
}

</script>