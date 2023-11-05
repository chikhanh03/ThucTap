<template>
    <div class="card">
        <div class="grid grid-cols-2 gap-10">
            <div class="p-7">
                <img :src="product.image" alt="product img" class="mx-auto my-7">
            </div>
            <div class="p-7">
                <h2 class="text-4xl my-7">{{ product.title }}</h2>
                <p class="text-xl my-7">Price - ${{ product.price }}</p>
                <h3 class="font-bold border-b-2 mb-4 pb-2">Product Description:</h3>
                <p class="mb-7">{{ product.description }}</p>
                <button class="bg-sky-500 hover:bg-sky-700 rounded-lg h-10 w-60">
                    Thêm vào giỏ hàng
                </button>
            </div>
        </div>
    </div>
</template>

<script setup>
    const { product } = defineProps(['product'])
</script>

<style scoped>
    img{
        max-width: 400px;
    }
    .bg-sky-500 {
    background-color: #0ea5e9;
    }
    .hover\:bg-sky-700:hover {
     background-color: #0369a1;
    }
</style>