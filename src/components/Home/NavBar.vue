<script setup lang="ts">
</script>

<template>
    <div class="sticky top-0 z-50 bg-white/60 backdrop-blur-md w-full shadow-sm">
        <header class="flex justify-between items-center px-8 py-4 max-w-7xl mx-auto">
            <a href="#inicio" class="shrink-0">
                <img src="../../assets/logo.png" alt="Logo" class="w-20 md:w-24 h-auto object-contain">
            </a>

            <nav class="flex items-center gap-8 font-medium">
                <a href="#inicio" class="hover:text-brand-pink transition-colors">Início</a>
                <a href="#sobre" class="hover:text-brand-pink transition-colors">Sobre</a>
                <button class="bg-brand-pink p-1.5 pl-4 pr-4 rounded-md text-white hover:scale-105 cursor-pointer transition-transform">Entrar</button>
                <!-- <button
                    class="border border-gray-200 rounded-full px-6 py-2 text-sm hover:bg-gray-50 transition-colors">
                    Admin
                </button>

                <button
                    class="bg-brand-light text-brand-pink rounded-full w-10 h-10 flex items-center justify-center hover:opacity-80 transition-opacity">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z"
                            clip-rule="evenodd" />
                    </svg>
                </button> -->
            </nav>
        </header>
    </div>
</template>