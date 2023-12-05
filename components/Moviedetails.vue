<script setup >
    defineProps(["titel", "date", "poster", "revenue", "overview"]);
</script>

<template>
    <div>
        <div class="grid sm:grid-cols-3 gap-7 justify-items-center m-10">
            <!-- Column 1: Image -->
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <img
                    class="h-[400px] w-full object-cover"
                    :src="poster" 
                    alt="Placeholder image">
            </div>
             <!-- Column : titel , overview , revenue , buy button -->
            <div class="sm:col-span-2 mx-6">
                <h1 class="font-bold text-2xl mb-5">{{ titel }}</h1>
                <h3 class="font-semibold text-lg mb-8">Release Date : {{ date }}</h3>
                <p class="text-gray-500 text-md mb-8">{{ overview}}
                </p>
                <p class="text-gray-500 text-md">Revenue: {{ revenue }}</p>
                <div>
                    <NuxtLink 
                        to="https://www.youtube.com/watch?v=mqqft2x_Aa4"
                        target="_blank"
                        class="bg-indigo-500 hover:bg-indigo-600 text-white
                        font-medium py-2 px-4 rounded"
                    >
                    Watch Trailer
                    </NuxtLink>
                     <button
                        class="bg-rose-500 hover:bg-rose-600 text-white
                        font-medium py-2 px-4 rounded m-5"
                    >
                    Bay Now
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<style  scoped>

</style>