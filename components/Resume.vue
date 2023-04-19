<template>
    <section class="resume">
        <!-- <section class="left">
            <ResumeSkills :skills="skills" />
            <ResumeCertifications :certs="certs" />
        </section>

        <section class="right">
            <ResumeWorkExperience
                :workPlace="workPlace"
                :yearFrom="yearFrom"
                :yearTo="workTo"
                :role="role"
                :tasks="tasks"
            />
            <slot />
        </section> -->
        <slot />
    </section>
</template>

<!-- <script>
export default {
        props: {
            certs: {
                type: Array,
                default: "uhhh.",
            },
            skills: {
                type: Array,
                default: "some skills here please.",
            },
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
</script> -->
