<template>
    <section class="skills">
        <h3>Design</h3>

        <ul>
            <li v-for="skills in skills" :key="skills">{{ skills }}</li>
        </ul>
    </section>
</template>

<script>
export default {
    props: {
        skills: {
            type: Array,
            default: "Put your skills here.",
        },
    },
};
</script>
