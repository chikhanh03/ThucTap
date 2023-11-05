<template>
    <div class="card text-center">
        <img :src="product.image" alt="product thumb" class="thumb"> 
        <p class="font-bold text-gray-500 m-4 truncate">{{ product.title }}</p>
        <NuxtLink :to="`/products/${product.id}`">
            <p class="btn my-4 ">View Detail</p>
        </NuxtLink>
    </div>
</template>

<script setup>
    const { products } = defineProps(['product'])
</script>

<style scoped>
    .thumb{
        max-height: 150px;
        max-width: 100%;
        margin: 0 auto;
    }
</style>