<template>
    <button id="close-button" class="close-menu" @click="closeMenu()">
        <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-x"
        >
            <line x1="18" y1="6" x2="6" y2="18"></line>
            <line x1="6" y1="6" x2="18" y2="18"></line>
        </svg>
    </button>
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
