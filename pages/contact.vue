<script setup >
definePageMeta({
        layout: "custom",
    });
</script>

<template>
    <div>
        <div class="bg-gray-100">

    <div class="bg-cover bg-center ">
        <img src="~assets/images/comtact-image.jpg" alt="" class="h-52 w-full">
        <!-- Replace 'your-image-url.jpg' with the URL or path to your image -->
    </div>

    <div class="container mx-auto p-8  bg-white rounded shadow-md">

        <h2 class="text-2xl font-semibold mb-4">Contact Us</h2>

        <form action="#" method="POST">

            <div class="mb-4">
                <label for="name" class="block text-sm font-medium text-gray-600">Your Name</label>
                <input type="text" id="name" name="name" class="mt-1 p-2 w-full border rounded-md">
            </div>

            <div class="mb-4">
                <label for="email" class="block text-sm font-medium text-gray-600">Your Email</label>
                <input type="email" id="email" name="email" class="mt-1 p-2 w-full border rounded-md">
            </div>

            <div class="mb-4">
                <label for="message" class="block text-sm font-medium text-gray-600">Your Message</label>
                <textarea id="message" name="message" rows="4" class="mt-1 p-2 w-full border rounded-md"></textarea>
            </div>

            <button type="submit" class="bg-blue-500 text-white p-2 rounded-md w-full">Send Message</button>

        </form>

    </div>

</div>
    </div>
</template>

<style lang="scss" scoped>

</style>