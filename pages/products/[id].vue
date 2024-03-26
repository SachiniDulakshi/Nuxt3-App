<template>

    <div>
        <h1>Product details</h1>
        <p>Product details for {{id}} </p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit et non expedita consequatur ipsa deserunt maxime sed quibusdam at necessitatibus, asperiores temporibus adipisci delectus praesentium aliquid facere vero, consequuntur voluptas?</p>
    </div>
</template>

<script setup>
    const {id} = useRoute().params

    definePageMeta({
    layout: 'products',
})
</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }

    p {
        margin: 20px 0;
    }
</style>