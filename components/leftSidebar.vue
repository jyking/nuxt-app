<template>
    <div class="flex flex-col w-40 h-full">
        <div class="flex border">网址导航</div>
        <div class="flex h-full bg-gray-700 p-6 w-40 md:w-64">
            <ul>
                <li v-for="menu in menus">
                    <a class="flex items-center" href="#">
                        <img class="h-6 mr-2" :src=menu.icon />
                        <div class="text-gray-400">{{ menu.font }}</div>
                    </a>
                </li>
            </ul>
        </div>
        <div class="flex border h-32">底</div>
    </div>
</template>

<script setup>
const menus = [
    { icon: "/img/1.svg", font: "测试A" },
    { icon: "/img/1.svg", font: "测试B" },
]
</script>
