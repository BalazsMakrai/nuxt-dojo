<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="p4 mx-auto container">
                <NuxtLink to="/product" class="font-bold">Nuxt Dojo Merch</NuxtLink>
            </nav>
        </header>
        <div class="p4 mx-auto container">
            <slot />
        </div>
        <footer class="container mx-auto p4 flex justify-between border-t-2">
            <ul class="flex gap-4">
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/products">Products</NuxtLink>
                </li>
            </ul>
        </footer>
    </div>
</template>

<script setup>

</script>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>