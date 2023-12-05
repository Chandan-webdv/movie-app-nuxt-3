<script setup >
definePageMeta({
        layout: "custom",
    });
</script>

<template>
    <div>
        <div class="bg-gray-100 h-screen flex items-center justify-center">

    <div class="bg-white p-8 rounded shadow-md w-96">

        <h2 class="text-2xl font-semibold mb-4">Register</h2>

        <form action="#" method="POST">

            <div class="mb-4">
                <label for="username" class="block text-sm font-medium text-gray-600">Username</label>
                <input type="text" id="username" name="username" class="mt-1 p-2 w-full border rounded-md">
            </div>

            <div class="mb-4">
                <label for="email" class="block text-sm font-medium text-gray-600">Email</label>
                <input type="email" id="email" name="email" class="mt-1 p-2 w-full border rounded-md">
            </div>

            <div class="mb-4">
                <label for="password" class="block text-sm font-medium text-gray-600">Password</label>
                <input type="password" id="password" name="password" class="mt-1 p-2 w-full border rounded-md">
            </div>

            <div class="mb-4">
                <label for="confirm-password" class="block text-sm font-medium text-gray-600">Confirm Password</label>
                <input type="password" id="confirm-password" name="confirm-password" class="mt-1 p-2 w-full border rounded-md">
            </div>

            <button type="submit" class="bg-blue-500 text-white p-2 rounded-md w-full">Register</button>

        </form>

    </div>

        </div>
    </div>
</template>

<style  scoped>

</style>