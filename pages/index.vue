<template>
    <Html class="h-full"></Html>
    <Body class="flex h-full"></Body>
    
    <div class="flex flex-row h-full bg-gray-300 text-gray-600">
        <LeftSidebar />
        <div class="body w-full">
            <div class="header">网址导航</div>
            <div class="main ">main</div>
        </div>
    </div>
</template>

<script setup>
const title = ref('Hello World')
</script>