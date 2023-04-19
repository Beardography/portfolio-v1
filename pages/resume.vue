<template>
    <Resume>
        <section class="left">
            <h1>Skills</h1>
            <ResumeSkills
                skillType="Design"
                :skills="[
                    'Figma',
                    'Penpot',
                    'Adobe XD',
                    'Photo Shop / Affinity Photo',
                    'Adobe Illustrator / Affinity Designer',
                    'Adobe InDesign / Affinity Publisher',
                    'Lightroom / Darktable',
                ]"
            />

            <ResumeSkills
                skillType="Development"
                :skills="[
                    'VS Code',
                    'HTML',
                    'CSS / SCSS / Less',
                    'JavaScript',
                    'Vue',
                    'Nuxt',
                    'React',
                    'Git',
                ]"
            />

            <h1>Certificates</h1>
            <ResumeCertifications
                year="2022"
                :certs="[
                    'NN/g Group - UX Certificate',
                    'Codecademy - Learn JavaScript Course',
                    'Codecademy - Learn Vue.js',
                ]"
            />

            <ResumeCertifications
                year="2021"
                :certs="[
                    'Codecademy - How to Deploy a Website',
                    'Codecademy - Learn Bootstrap',
                    'Codecademy - Learn CSS',
                    'Codecademy - Learn Color Design',
                    'Codecademy - Learn Git',
                    'Codecademy - Learn HTML',
                    'Codecademy - Learn Navigation Design',
                    'Codecademy - Learn Responsive Design',
                    'Codecademy - Learn SQL',
                    'Codecademy - Learn Sass',
                    'Codecademy - Learn Command Line',
                ]"
            />
        </section>

        <section class="right">
            <ResumeWorkExperience
                workPlace="Kiewit"
                yearFrom="2018"
                yearTo="2023"
                role="UI Designer"
                :tasks="[
                    'Worked on Kiewit UI Design System',
                    'Worked on HR related software to provide future growth to Kiewit employees',
                    'Designed UI to help manage equipment and people moving between job-sites to help forecast most cost effective plans',
                    'Hand off design specs to work with developers to create consistency between the design and final product',
                ]"
            />

            <ResumeWorkExperience
                workPlace="Sandhills"
                yearFrom="2017"
                yearTo="2018"
                role="Interactive Designer"
                :tasks="[
                    'Worked directly with sales reps and clients to design mock-ups for potential websites',
                    'Developed new websites as well as overall redesigns of existing websites for clients',
                    'Utilized SEO processes to optimize client\'s website to reach more potential customers',
                    'Developed websites that are optimized to be viewed and utilized across desktop and mobile',
                    'Proof code to make sure it meets standards, and makesure it\'s compatible across different browsers and devices',
                    'Perform website updates as requested',
                ]"
            />

            <ResumeWorkExperience
                workPlace="Conagra Brands"
                yearFrom="2015"
                yearTo="2017"
                role="Visual Learning Developer"
                :tasks="[
                    'Design media to brand and promote different departments and events within organization',
                    'Shoot video with Executive Management to promote upcoming projects within organization',
                    'Worked with Executive Management to create and manage media for upcoming internal projects',
                    'Worked with Executive Management to standardize interactive PDF for performance forms',
                    'Collaborated with managers to design, develop, and promote learning courses and other content',
                    'Created content and graphics for presentations used by Executive management to present to entire organization',
                ]"
            />
        </section>
    </Resume>
</template>
