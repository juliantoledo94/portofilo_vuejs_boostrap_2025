<script setup>

import linkedinIcon from "@/assets/imgs/icons/linkedin.png"
import githubIcon from "@/assets/imgs/icons/github.png"


</script>


<template>

    <section class="container mt-5">
        <div class="">

            <div class="row mt-5">
                <div class="col-12 col-xl-6 d-flex justify-content-center align-items-center">
                    <div class="circlediv">

                        <!-- <img class="w-100" :src="profilePicture" alt="Julian's profile picture"> -->
                    </div>
                </div>
    
                <div class="col-12 col-xl-6 d-flex flex-column justify-content-center justify-content-xl-center mt-5 mt-xl-0 align-items-center">
                    <div class="d-flex flex-column">
                        <h1 class="order-2 ">Julian Toledo</h1>
                        <p class="order-1 text-center text-secondary m-0 small fw-bold">Hello, i'm</p>
                        <p class="order-3 text-center text-secondary m-0 small fw-bold">Full Stack Developer</p>
                    </div>
                    <div class="d-flex mt-4 gap-3 align-items-center justify-content-center">
                        <div class="mediaSizes">
                            <a href="https://www.linkedin.com/in/juliandavidtoledo/" target="_blank">
                                <img class="w-100" :src="linkedinIcon" alt="">
                            </a>
                        </div>
                        <div class="mediaSizes">
                            <a href="https://github.com/juliantoledo94" target="_blank">
                                <img class="w-100" :src="githubIcon" alt="">
                            </a>
                        </div>
                    </div>
    
                </div>
            </div>
        </div>
    </section>



</template>


<style scoped>
    .circlediv{
        width: 400px;
        height: 400px;
        border-radius: 50%;
        overflow: hidden;
        background-image: url("@/assets/imgs/julian/julian.webp");
        background-size: cover;
        background-position-y: -50px;
        
        
    }

    h1{
        font-size: 5rem;
    }

    .mediaSizes{
        width: 50px;
    }
</style>