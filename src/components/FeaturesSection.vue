<template>
    <div id="features" class="offset">
        <div class="jumbotron">
            <div class="narrow text-center">
                <div class="col-md-12 text-center">
                    <h3 class="heading">Why should I use Vue JS?</h3>
                    <div class="heading-underline"></div>
                </div>
                <div class="row text-center">
                    <div class="col-md-4">
                        <div class="feature">
                            <i
                                class="fas fas fa-diagnoses fa-4x"
                                data-fa-transform="shrink-3 up-5"
                            ></i>
                            <h3>Gentle Learning Curve</h3>
                            <p>
                                All you really need to get going is a basic understanding of JavaScript, HTML, and CSS.
                            </p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="feature">
                            <i
                                class="fas fa-laptop-code fa-4x"
                                data-fa-transform="shrink-4.5 up-4.5"
                            ></i>
                            <h3>Rich of Libraries</h3>
                            <p>
                                With a rich collection of libraries and set of tools facilitating development, the Vue world has everything a developer needs.
                            </p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="feature">
                            <i
                                class="fas fa-mobile-alt fa-4x"
                                data-fa-transform="shrink-4 up-5"
                            ></i>
                            <h3>Mobile Development</h3>
                            <p>
                                Vue offers developers a few solutions for cross-platform mobile UI development.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: "features"
};
</script>
<style scoped>
#features .narrow{
    padding-top: 0;
}
#features:before {
    display: block;
    content: "";
    height: 3.7rem;
    margin-top: -3.7rem;
}
.feature h3 {
    font-size: 1.3rem;
    text-transform: uppercase;
    padding-bottom: 0.4rem;
}
.feature p {
    font-size: 1.1rem;
}
</style>
