<template>
    <div class="w-3/4 text-[#FFEFD3] flex justify-evenly items-center flex-col ">
        <h1 class="text-4xl ">Welcome to the home clicker</h1>

        <div>
            <NuxtLink to="/clickerCookie" v-model="clickCookie" class="flex justify-center rounded-md bg-[#294C60] px-6 py-4 font-semibold leading-6xl shadow-sm hover:bg-[#1f3a4a] focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2">Cookie World</NuxtLink>
            <br>
            <NuxtLink to="/clickerUnicorn" v-model="clickUnicorn" class="flex justify-center rounded-md bg-[#294C60] px-6 py-4 font-semibold leading-6xl shadow-sm hover:bg-[#1f3a4a] focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2">Unicorn World</NuxtLink>
        </div>
    </div>
</template>

<script>



</script>