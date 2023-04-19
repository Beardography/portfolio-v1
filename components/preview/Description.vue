<template>
    <section class="description">
        <h3>Year: {{ year }}</h3>
        <p>
            {{ description }}
        </p>
    </section>
</template>

<script>
export default {
    props: {
        description: {
            type: String,
            default: "Place description here.",
        },

        year: {
            type: Number,
            default: 9999,
        },
    },
};
</script>
