<template>
    <nav class="mobile-nav hidden">
        <NavigationCloseMenuButton />
        <ul>
            <li @click="closeMenu()"><NuxtLink to="/">Home</NuxtLink></li>
            <li @click="closeMenu()"><NuxtLink to="/about">About</NuxtLink></li>
            <li @click="closeMenu()">
                <NuxtLink to="/resume">Resume</NuxtLink>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    methods: {
        closeMenu() {
            const nav = document.querySelector(".mobile-nav");
            const openButton = document.querySelector("#open-button");
            const closeButton = document.querySelector("#close-button");
            nav.classList.remove("open");
            // openButton.classList.remove("hidden");
            // closeButton.classList.add("hidden");
        },
    },
};
</script>
