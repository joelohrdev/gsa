<template>
    <div class="max-w-7xl mx-auto mb-10">
        <div class="flex justify-between items-center py-3">
            <NuxtLink to="/"><img src="/logo.png" alt="Logo" class="w-32" /></NuxtLink>
            <div>
                <ul class="flex space-x-5">
                    <li class="hover:text-maroon transition"><NuxtLink to="/">Home</NuxtLink></li>
                    <li class="hover:text-maroon transition"><NuxtLink to="/about">About</NuxtLink></li>
                    <li class="hover:text-maroon transition"><NuxtLink to="/gallery">Gallery</NuxtLink></li>
                    <li class="hover:text-maroon transition"><NuxtLink to="/contact">Contact</NuxtLink></li>
                </ul>
            </div>
        </div>
    </div>
</template>