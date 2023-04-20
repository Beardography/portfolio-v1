<template>
    <div class="nav">
        <header class="header">
            <h1><NuxtLink to="/">Name.xyz</NuxtLink></h1>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/resume">Resume</NuxtLink></li>
            </ul>
            <NavigationOpenMenuButton />
        </header>
        <NavigationMobileNav />
    </div>
</template>
