<script setup>
import { ref } from 'vue';
import CButton from './components/CButton.vue';
import Header from './components/Header.vue';
import Landing from './components/Landing.vue';

const count = ref(0);
</script>


<template>
	<div>
    <Header />
	<Landing />
	</div>
</template>

