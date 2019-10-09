<template>
    <div id="contact" class="offset">
        <footer>
            <div class="row justify-content-center">
                <div class="col-md-5 text-center">
                    <img src="../assets/images/logo.png" />
                    <p>
                        At our core is a collection of design and development
                        solutions that represent everything your business needs
                        to compete in the modern marketplace.
                    </p>
                    <strong>Contact Info.</strong>
                    <p>(000) 000-0000<br />email@email.com</p>
                    <a href="#"><i class="fab fa-facebook-square"></i></a>
                    <a href="#"><i class="fab fa-twitter-square"></i></a>
                    <a href="#"><i class="fab fa-youtube-square"></i></a>
                </div>
            </div>
            <hr class="footer-hr" />
            <p class="text-center">Vue Theme &copy; 2019</p>
        </footer>
    </div>
</template>
<script>
export default {
    name: "contact"
};
</script>
<style scoped>
#contact:before{
    display: block;
    content: "";
    height: 1.6rem;
    margin-top: -1.6rem;
}
footer {
    background-color: #40474e;
    color: white;
    padding: .7rem 0;
    margin-top: 2rem;
}
footer img{
    width: 100%;
    margin-top: 1.5rem;
}
footer a{
    color: white;
}
footer svg.svg-inline--fa{
    font-size: 1.6rem;
    margin: 1.2rem .5rem 0 0;
}

footer svg.svg-inline--fa:hover{
    color: #1ebba3 !important;
}
</style>
