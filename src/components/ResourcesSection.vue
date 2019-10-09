<template>
    <div id="resouces" class="offset">
        <div class="fixed-background">
            <div class="row dark text-center">
                <div class="col-md-12">
                    <h3 class="heading">Build With Care</h3>
                    <div class="heading-underline"></div>
                </div>
                <div class="col-md-4">
                    <h3>HTML 5</h3>
                    <div class="feature">
                        <i class="fas fa-code fa-3x"></i>
                    </div>
                    <p class="lead">Build With the latest, HTML 5</p>
                </div>
                <div class="col-md-4">
                    <h3>Bootstrap 4</h3>
                    <div class="feature">
                        <i class="fas fa-bold fa-3x"></i>
                    </div>
                    <p class="lead">Build With the latest, BOOTSTRAP 4</p>
                </div>
                <div class="col-md-4">
                    <h3>CSS 3</h3>
                    <div class="feature">
                        <i class="fab fa-css3 fa-3x"></i>
                    </div>
                    <p class="lead">Build With the latest, CSS 3</p>
                </div>
            </div>
            <div class="overlay"></div>
        </div>
    </div>
</template>
<script>
export default {
    name: "resouces"
};
</script>
<style scoped>
#resouces:before {
    display: block;
    content: "";
    height: 3.6rem;
    margin-top: -3.6rem;
}
.fixed-background {
    position: relative;
    background-image: url("../assets/images/home-bg.jpg");
    background-attachment: fixed;
    background-size: cover;
    background-repeat: no-repeat;
}
.dark{
    background-color: rgba(0, 0, 0, 0.75);
    color: white; 
    padding: 7rem 2rem;
}
.fixed-background h3 {
}

.fixed-background p {
}
</style>
