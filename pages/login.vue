<script setup >
    definePageMeta({
        layout: "custom",
    });
</script>

<template>
    <div>
        <div class="w-full max-w-md mx-auto mt-5">
            <form action="" class="bg-white shadaw-md rounded px-8 pt-6 pb-8 mb-4">
                <div class="mb-4">
                    <label for="username" class="block text-gray-700 font-bold mb-2">
                        User name
                    </label>
                    <input  
                    class="shadow appearance-none border rounded w-full
                    py-2 px-3 text-gray-700 leading-tight focus:outline-none
                    focus:shadow-outline"
                    id="username"
                    type="text"
                    placeholder="Username"
                    >
                </div>
                <div class="mb-4">
                    <label for="password" class="block text-gray-700 font-bold mb-2">
                        password
                    </label>
                    <input  
                    class="shadow appearance-none border rounded w-full
                    py-2 px-3 text-gray-700 leading-tight focus:outline-none
                    focus:shadow-outline"
                    id="password"
                    type="password"
                    placeholder="password"
                    >
                </div>
                <div class="flex item-center justify-center mt-6">
                    <button 
                        class="bg-rose-500 hover:bg-rose-700 text-white
                        font-bold py-2 px-8 rounded-full focus:outline-none
                        focus:shadow-outline"
                        type="button"
                    >
                        LogIn
                    </button>
                </div>
            </form>
        </div>
    </div>
</template>

<style  scoped>

</style>