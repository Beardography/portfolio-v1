<template>
    <Resume>
        <ResumeCertifications
            :certs="['Cert 1', 'Cert 2', 'Cert 3', 'Cert 4']"
        />

        <ResumeSkills :skills="['skill 1', 'skill 2', 'skill 3', 'skill 4']" />

        <ResumeWorkExperience
            workPlace="workPlace"
            yearFrom="2020"
            yearTo="2023"
            role="UI Designer"
            :tasks="['task 1', 'task 2', 'task 3', 'task 4']"
        />
    </Resume>
</template>
