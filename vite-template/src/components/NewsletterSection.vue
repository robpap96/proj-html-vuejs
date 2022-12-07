<script>
export default {
    name: 'NewsletterSection',
    components: {

    },
    defineProps :{
        //msg: String
    },
    data(){
        return {
            //
        }
    },


}
</script>

<template>
    <section class="newsletter-section">
        <div class="container">
            <div class="row justify-content-center">
                <div class="offset-3"></div>
                <div class="col-6 my-5">
                    <h2 class="my-5 text-center">Sign up to our Newsletter</h2>
                    <div class="newsletter-input">
                        <input class="form-control form-control-lg" type="text" aria-label=".form-control-lg example">
                    </div>

                </div>
                <div class="offset-3"></div>
                <div class="offset-3"></div>
                <div class="col-6">
                    <button type="submit" class="my-btn">SUBSCRIBE</button>
                </div>
                <div class="offset-3"></div>
                <div class="col-6 text-center py-2">
                    <small>(We don't share share your data with anybody, and only use it for its intendend purpose)</small>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    .newsletter-section {
        background-image: url('../assets/newsletter_background.jpg');
        background-size: cover;
        background-repeat: no-repeat;
    }

    .my-btn {
        width: 100%;
        background-color:#7abc64;
        border-radius:23px;
        border:2px solid #7abc64;
        display:inline-block;
        cursor:pointer;
        color:#ffffff;
        font-family:Arial;
        font-size:16px;
        padding:10px 48px;
        text-decoration:none;
        text-shadow:0px 0px 2px #2f6627;
    }
    .my-btn:hover {
        background-color:#ffffff;
        color: #7abc64;
    }
    .my-btn:active {
        position:relative;
        top:1px;
    }
    small{
        font-weight: 100;
        color: 92aec8;
    }
</style>