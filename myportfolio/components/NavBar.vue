<template>
    <!--NAVBAR-->
    <header class="sticky top-0 z-50 flex justify-between items-center space-x-3 border-b bg-white p-4 shadow-md">
        <a class="text-3xl font-mono" href="/">ポートフォリオ</a>
        <div class="flex space-x-4">
            <a href="/"
                class="-mx-3 block rounded-lg py-2 px-3 text-base font-semibold leading-7 text-pink-900 hover:bg-gray-50">home</a>
            <NuxtLink to="/about/about"
                class="-mx-3 block rounded-lg py-2 px-3 text-base font-semibold leading-7 text-pink-900 hover:bg-gray-50">
                about</NuxtLink>
            <NuxtLink to="/works/works"
                class="-mx-3 block rounded-lg py-2 px-3 text-base font-semibold leading-7 text-pink-900 hover:bg-gray-50">
                skills</NuxtLink>
            <NuxtLink to="/contact/contact"
                class="-mx-3 block rounded-lg py-2 px-3 text-base font-semibold leading-7 text-pink-900 hover:bg-gray-50">
                contact</NuxtLink>
        </div>
    </header>
    <!--NAVBAR-->
</template>