<template>
    <button id="open-button" class="open-menu" @click="openMenu()">
        <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="white"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-menu"
        >
            <line x1="3" y1="12" x2="21" y2="12"></line>
            <line x1="3" y1="6" x2="21" y2="6"></line>
            <line x1="3" y1="18" x2="21" y2="18"></line>
        </svg>
    </button>
</template>

<script>
export default {
    methods: {
        openMenu() {
            const nav = document.querySelector(".mobile-nav");
            const openButton = document.querySelector("#open-button");
            const closeButton = document.querySelector("#close-button");

            nav.classList.add("open");
            // openButton.classList.add("hidden");
            // closeButton.classList.remove("hidden");
        },
    },
};
</script>
