<template>
    <div>
        <h1>Product details for {{id}}</h1>
    </div>
</template>

<script setup>
const route = useRoute();
const {id} = route.params
</script>

<style scoped>

</style>