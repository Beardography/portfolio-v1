<template>
    <section class="project-details">
        <h3>Project 0{{ projectNumber }}/10</h3>
        <ul>
            <li><strong>Project Type:</strong> {{ projectType }}</li>
            <li><strong>Role:</strong> UI Designer, UI Developer</li>
            <li><strong>Deliverables:</strong> Wireframe, Website</li>
        </ul>
    </section>
</template>

<script>
export default {
    props: {
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
        projectNumber: {
            type: Number,
            default: 1,
        },
    },
};
</script>
