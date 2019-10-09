<template>
    <div id="clients" class="offset">
        <div class="jumbotron">
            <div class="col-md-12 text-center">
                <h3 class="heading">Clients</h3>
                <div class="heading-underline"></div>
            </div>
            <div class="row narrow">
                <div class="col-md-6 client">
                    <div class="row">
                        <div class="col-md-4">
                            <img src="../assets/images/client1.jpg" />
                        </div>
                        <div class="col-md-8">
                            <blockquote>
                                <i class="fas fa-quote-left"></i>
                                I see vue support as more of a partener to my
                                company than a reource. I can pick up the phone
                                and talk to anyone at any time and the way that
                                they iteract with us as a business makes it
                                really simple.
                                <hr class="client-hr" />
                                <cite>&#8212; Eric, Small Business Owner</cite>
                            </blockquote>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 client">
                    <div class="row">
                        <div class="col-md-4">
                            <img src="../assets/images/client1.jpg" />
                        </div>
                        <div class="col-md-8">
                            <blockquote>
                                <i class="fas fa-quote-left"></i>
                                I see vue support as more of a partener to my
                                company than a reource. I can pick up the phone
                                and talk to anyone at any time and the way that
                                they iteract with us as a business makes it
                                really simple.
                                <hr class="client-hr" />
                                <cite>&#8212; Eric, Small Business Owner</cite>
                            </blockquote>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-md-12 narrow text-center">
            <p class="lead">
                Want to learn more about developeing Vuejs Library?
            </p>
            <a class="btn btn-secondary btn-md start-now-btn">Start Now</a>
        </div>
    </div>
</template>
<script>
export default {
    name: "clients"
};
</script>
<style>
#clients:before {
    display: block;
    content: "";
    height: 3.7rem;
    margin-top: -3.7rem;
}
#clients .jumbotron {
    padding-bottom: 0;
}
#clients .narrow {
    width: 90%;
}
.client img {
    display: block;
    width: 80%;
    border-radius: 50%;
    margin: auto;
}
blockquote .svg-inline--fa {
    color: #1ebba3;
    margin: 0.3rem;
}
.client-hr {
    border-top: 0.05rem solid #1ebba3;
}
</style>
