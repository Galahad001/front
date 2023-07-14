<template>
    <div>
        <p>Product datails for {{ id }}</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

    definePageMeta({
            layout:'products'
        })

</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 40px;
    }

    p {
        margin: 20px, 0;
        color: rebeccapurple;
    }

</style>