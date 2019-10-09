<template>
    <div id="app">
        <HomeSection />
        <CoursesSection />
        <FeaturesSection />
        <ResourcesSection />
        <ClientsSection />
        <ContactSection />
    </div>
</template>

<script>
import HomeSection from "./components/HomeSection.vue";
import CoursesSection from "./components/CoursesSection.vue";
import FeaturesSection from "./components/FeaturesSection.vue";
import ResourcesSection from "./components/ResourcesSection.vue";
import ClientsSection from "./components/ClientsSection.vue";
import ContactSection from "./components/ContactSection.vue";
export default {
    name: "app",
    components: {
        HomeSection,
        CoursesSection,
        FeaturesSection,
        ResourcesSection,
        ClientsSection,
        ContactSection
    }
};
</script>
<style>
html {
    scroll-behavior: smooth;
}
body {
    overflow-x: hidden;
    color: #505962;
    font-family: "Noto Sans", sans-serif;
}
.offset:before {
    display: block;
    content: "";
    height: 4rem;
    margin-top: -4rem;
}
.narrow {
    width: 75%;
    margin: 1.5rem auto;
    padding-top: 2rem;
}
.narrow h1 {
    font-size: 2.4rem;
}
.jumbotron {
    margin-top: 0;
    margin-bottom: 0;
    padding: 2rem 0 3.5rem;
    border-radius: 0;
}
.btn-lg {
    border-width: medium;
    border-radius: 0;
    padding: 0.6rem 1.3rem;
    font-size: 1.1rem;
}
.btn-secondary {
    border-width: medium;
    border-radius: 0;
    text-transform: uppercase;
    font-size: 1.2rem;
    padding: 0.6rem 1.2rem;
    margin: 1rem;
    color: white !important;
    background-color: #1ebba3;
    border-color: #1ebba3;
}
.btn-md {
    border-radius: 2rem;
}
.btn-lg:hover,
.btn-secondary:hover {
    background-color: #189582;
    border-color: #189582;
}
h3.heading {
    font-size: 1.9rem;
    font-weight: 700;
    text-transform: uppercase;
    /* margin-bottom: 1.9rem; */
}
.heading-underline {
    width: 12rem;
    height: 0.2rem;
    background-color: #1ebba3;
    margin: 0 auto 2rem;
}
.feature svg.svg-inline--fa {
    color: #1ebba3;
}
</style>
