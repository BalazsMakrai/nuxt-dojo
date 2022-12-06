<template>
    <div>
        <p>Product detail for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia enim harum labore vel aliquam. Qui.</p>
    </div>
</template>

<script setup>
definePageMeta({
    layout: 'products'
});
const { id } = useRoute().params;
</script>

<style scoped>

</style>