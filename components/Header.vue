<template>
    <header class="sticky top-0 z-20 border-b backdrop-blur">
        <div class="container flex h-16 items-center justify-between">
            <!--Logo-->
            <div class="flex items-center gap-3">
                <img src="/icons/logo.avif"  alt="Admin Dashboard" class="h-14 w-14 object-contain" />
                <NuxtLink to="/" class="text-xl font-bold"> Admin Dashboard </NuxtLink>
            </div>
        </div>
        <!--Right Side-->
        <div class="flex items-center gap-5">
            <button class="flex h-9 w-9 shrink-0 items-center justify-center rounded-full border">
                button
            </button>
        </div>
    </header>
</template>

<script setup>
</script>