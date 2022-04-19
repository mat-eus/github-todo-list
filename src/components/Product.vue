<template lang='pug'>
    div.product-image
        img(v-bind:src="productImage")
    
    div.product-info
        p(v-text="productName")
</template>

<script>
    export default {
        name: 'Product',
        props: {
            productName: String,
            productImage: String
        }
    }
</script>

<style>
    .product-image{
        border-radius: 10%;
    }
    .product-info{
        font-family: 'Courier New', Courier, monospace;
    }
</style>
