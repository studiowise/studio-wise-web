<script setup>
import { Head, Link } from '@inertiajs/vue3';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>

    <Head title="Welcome" />

    <div
        class="relative flex items-top justify-center min-h-screen bg-cover bg-center bg-[url('/images/bg4.jpg')] items-center p-5">
        <div
            class="w-full max-w-screen-sm backdrop-blur-2xl backdrop-saturate-150 bg-white bg-opacity-40 overflow-hidden rounded-2xl shadow-xl p-6">
            <div class="text-gray-700 text-center">
                <h1 class="text-4xl mb-5">Studio Wise</h1>
                <p>Coming soon</p>
            </div>
            <div></div>
        </div>
    </div>
</template>
