<template>
    <section class="certifications">
        <h3>{{ year }}</h3>

        <ul>
            <li v-for="certs in certs" :key="certs">{{ certs }}</li>
        </ul>
    </section>
</template>

<script>
export default {
    props: {
        year: {
            type: Number,
            default: 2020,
        },

        certs: {
            type: Array,
            default: "Put your certifications here.",
        },
    },
};
</script>
