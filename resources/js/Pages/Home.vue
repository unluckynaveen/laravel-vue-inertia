<script setup>
// import Home from '../../Pages/Home.vue';
import Layout from '../Layout/Layout.vue';
defineProps({
 name: String
});

defineOptions({ layout: Layout});

</script>

<template>
 <h1>Hello {{ name }}</h1>
</template>
