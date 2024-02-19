<template>
    <div class="bg-slate-100">
        <div class="w-screen h-screen relative before:absolute before:w-full before:h-full before:top-0 before:left-0
        before:bg-black/50 absolute:z-16">
            <img src="~/assets/img/home-bg.jpg" alt="" class="w-full h-full object-cover">
            <div class="absolute top-0 left-0 w-full h-full flex items-center justify-center z-30">
                <h2 class="text-5xl md:text-6xl font-extrabold text-white text-center px-2 animate__animated animate__fadeInLeft">WE ARE DIGITAL AGENCY</h2>
            </div>
        </div>

        <WhatAreWe />
        <portfolio />
        <Service />
        <Testimonial />
        <div class="py-10 border bg-slate-50">
            <div class="text-center p-10 ">
                <h1 class="text-4xl font-semibold mb-4" data-aos="fade-up">Do You Have Any Project In Mind?</h1>
                <p data-aos="fade-right">Elevate your digital aspirations with our proven expertise – contact us today to turn your
                     vision into a captivating reality.</p>

                <nuxt-link to="/contact" data-aos="fade-down" class="block mt-10 px-10 py-3 border-2 w-fit mx-auto hover:bg-slate-50">Contact us</nuxt-link>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>