<template>
    <div class="bg-gray-100 min-h-screen">
        <navbar />
        <main>
            <RouterView />
        </main>
    </div>
</template>

<script setup>
    import navbar from './navbar.vue'
</script>