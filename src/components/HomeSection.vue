<template>
    <!-- start Home Section -->
    <div id="home">
        <!-- Start navigation -->
        <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
            <a href="#home" class="navbar-brand">
                <img src="@/assets/images/logo.png" alt="Brand" />
            </a>
            <button
                type="button"
                class="navbar-toggler"
                data-toggle="collapse"
                data-target="#navbarResponsive"
            >
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collpase navbar-collapse" id="navbarResponsive">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a href="#home" class="nav-link">Home</a>
                    </li>
                    <li class="nav-item">
                        <a href="#courses"  class="nav-link">Courses</a>
                    </li>
                    <li class="nav-item">
                        <a href="#features"  class="nav-link">Features</a>
                    </li>
                    <li class="nav-item">
                        <a href="#resouces"  class="nav-link">Resouces</a>
                    </li>
                    <li class="nav-item">
                        <a href="#clients"  class="nav-link">Clients</a>
                    </li>
                    <li class="nav-item">
                        <a href="#contact"  class="nav-link">Contact</a>
                    </li>
                </ul>
            </div>
        </nav>
        <!-- End navigation -->

        <!-- Start Hero -->
        <div class="hero home-hero">
            <div class="overlay"></div>
        </div>
        <div class="caption text-center">
            <h1>Welcome To My Vue.js Land Page</h1>
            <h3>This Page Built Using Vuejs Library</h3>
            <a
                href="https://vuejs.org/v2/guide/"
                target="_blank"
                class="btn btn-outline-light btn-lg"
            >
                Start Learn Vuejs
            </a>
        </div>
        <!-- End Hero -->
    </div>
    <!-- end Home Section -->
</template>

<script>
export default {
    name: "home",
    mounted(){
        location.href = "/#home"
    }
};
</script>
<style scoped>
.navbar {
    text-transform: uppercase;
    font-weight: 700;
    font-size: 0.9rem;
    letter-spacing: 0.1rem;
    background-color: rgba(0, 0, 0, 0.7) !important;
}
.navbar-brand img {
    height: 2rem;
}
.navbar-toggler {
    outline: none !important;
}
.navbar-nav li {
    padding-right: 0.5rem;
}
.navbar .navbar-nav .nav-link {
    color: white;
    padding-top: 0.8rem;
}
.navbar .navbar-nav .nav-link.active,
.navbar .navbar-nav .nav-link:hover {
    color: #1ebba3;
    cursor: pointer;
}

.hero {
    height: 100vh;
    width: 100%;
    position: relative;
}
.hero .overlay {
    position: absolute;
    top: 0;
    height: 100vh;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.7);
}
.home-hero {
    background-image: url("../assets/images/home-bg.jpg");
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
.caption {
    position: absolute;
    top: 35%;
    width: 100%;
    color: white;
    text-transform: uppercase;
}
.caption h1 {
    font-size: 3.8rem;
    font-weight: bold;
    letter-spacing: 0.3rem;
    text-shadow: 0.1rem 0.1rem 0.8rem black;
    padding-bottom: 1rem;
}
.caption h3 {
    font-size: 2rem;
    text-shadow: 0.1rem 0.1rem 0.8rem black;
    padding-bottom: 1rem;
}
</style>
