<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
                <ul class="flex gap-4">
                    <li>
                        <NuxtLink to="/">Home Page</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about">Aboyt Page</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/product" class="btn">Product Page</NuxtLink>
                    </li>
                </ul>
            </nav>
        </header>
        <div class="container mx-auto p-4">
            <slot />
        </div>

        <Footer />
    </div>
</template>
  
<script setup>
import Footer from '../components/Footer.vue';


</script>