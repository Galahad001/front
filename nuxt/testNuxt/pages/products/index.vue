<template>
    <div>
        <h2>Products</h2>
       <ul>
        <li>Яблоки</li>
        <li>Бананы</li>
        <li>Персики</li>
        <li>Гранат</li>
        <li>Алкоголь</li>
       </ul>
    </div>
</template>
    

<script setup>
    definePageMeta({
        layout:'products'
    })

</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 40px;
    }

    ul>li {
        font-family: sans-serif;
        color: rgb(165, 127, 202);
    }

</style>