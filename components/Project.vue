<template>
    <section class="preview">
        <section class="top">
            <div class="left">
                <PreviewDetails
                    :projectNumber="projectNumber"
                    :projectType="projectType"
                    :deliverables="deliverables"
                    :role="role"
                />
            </div>

            <div class="title">
                <h1>{{ title }}</h1>
            </div>

            <div class="right">
                <PreviewDescription :description="description" :year="year" />
            </div>
        </section>

        <section class="bottom">
            <img :src="img" />
        </section>
    </section>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            default: "Project Name Here",
        },

        projectNumber: {
            type: Number,
            default: 1,
        },

        description: {
            type: String,
            default: "Place description here.",
        },

        year: {
            type: Number,
        },

        projectType: {
            type: String,
            default: "Project Type Here",
        },

        deliverables: {
            type: String,
            default: "Deliverables Here",
        },

        role: {
            type: String,
            default: "Role Here",
        },

        img: {
            type: String,
            default: "https://via.placeholder.com/800x600",
        },
    },
};
</script>
