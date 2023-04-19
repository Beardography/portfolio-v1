<template>
    <section class="work-experience">
        <h1>{{ workPlace }}</h1>
        <h3>Years Active: {{ yearFrom }} - {{ yearTo }}</h3>
        <h3>Role: {{ role }}</h3>

        <ul>
            <li v-for="tasks in tasks" :key="tasks">{{ tasks }}</li>
        </ul>
    </section>
</template>

<script>
export default {
    props: {
        workPlace: {
            type: String,
            default: "Place of Work",
        },

        yearFrom: {
            type: Number,
            default: 2020,
        },

        yearTo: {
            type: Number,
            default: 2023,
        },

        role: {
            type: String,
            default: "UI Designer",
        },

        tasks: {
            type: Array,
            default: "Put your tasks here.",
        },
    },
};
</script>
