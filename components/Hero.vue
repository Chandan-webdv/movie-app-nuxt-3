<script setup >

</script>

<template>
    <div>
        <dev class="relative hero-section bg-cover bg-center">
        <img src="~assets/images/movie-bg.jpg" alt="" class="bg-cover w-full h-[400px]">
            <div class="absolute top-0 w-full h-[100vh] sm:mx-auto sm:p-32 p-8">
                <h1 class="text-6xl font-bold text-rose-600 mb-4">Movilix</h1>
                <h3 class="text-lg font-bold text-black">
                    Unlimited movie, TV shows and more.
                </h3>
                <div class="mt-6">
                    <NuxtLink 
                        href="/registration"
                        class="bg-indigo-500 hover:bg-indigo-600 text-white
                        rounded-full font-medium py-2 px-4"
                    >
                        Get Started
                    </NuxtLink>
                </div>
            </div>

        </dev>
    </div>
</template>

<style  scoped>

</style>