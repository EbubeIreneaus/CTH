<template>
    <div>
        <h2 class="text-center text-4xl font-bold my-16">Testimonial</h2>
        <div class="w-[90%] mx-auto my-10">
            <swiper-container init="false" class="py-7">
                <swiper-slide class="mx-5">
                    <div class="border px-10 py-10 bg-white">
                        <div class="flex gap-5">
                            <img src="~/assets/img/person_placeholder.png" alt="" class="size-14">
                            <div>
                                <h2 class=" font-normal text-xl ">Samuel Ebuka</h2>
                                <p class="font-thin ">Digital Assets Inc</p>
                            </div>
                        </div>
                        <div>
                            <p class="font-thin my-3">
                                I can't express enough gratitude for the exceptional web development services 
                                provided by this Digital Agency. Their team's dedication and attention to 
                                detail turned our vision into a stunning reality. The website not only 
                                reflects our brand identity but also delivers a seamless user experience, 
                                exceeding our expectations. It's a testament to their expertise and commitment
                                 to excellence.
                            </p>
                        </div>
                    </div>
                </swiper-slide>

                <swiper-slide>
                    <div class="border px-10 py-10 bg-white">
                        <div class="flex gap-5">
                            <img src="~/assets/img/person_placeholder.png" alt="" class="size-14">
                            <div>
                                <h2 class=" font-normal text-xl ">Chukwudi Stanley</h2>
                                <p class="font-thin ">Nepto Assets Inc</p>
                            </div>
                        </div>
                        <div>
                            <p class="font-thin my-3">
                                Working with the Web Development team was a game-changer for our business. 
                                They translated our ideas into a user-friendly and feature-rich web 
                                application. The collaboration was seamless, and their ability to balance 
                                innovation with practicality resulted in an website that resonates with our 
                                audience. We're delighted with the outcome and look forward to continued
                                 success together
                            </p>
                        </div>
                    </div>
                </swiper-slide>  

                 <swiper-slide class="mx-5">
                    <div class="border px-10 py-10 bg-white">
                        <div class="flex gap-5">
                            <img src="~/assets/img/person_placeholder.png" alt="" class="size-14">
                            <div>
                                <h2 class=" font-normal text-xl ">Andrea</h2>
                                <p class="font-thin ">Golden Wealths</p>
                            </div>
                        </div>
                        <div>
                            <p class="font-thin my-3">
                                Working with this Digital Agency has been a game-changer for our online
                                 presence. Their web development team exceeded our expectations, delivering a 
                                 visually stunning website that perfectly aligns with our brand. The seamless 
                                 blend of aesthetics and functionality truly sets them apart in the digital
                                  realm. The collaborative approach and attention to detail have made this 
                                  partnership invaluable. Our digital journey wouldn't be the same without
                                   their expertise.
                            </p>
                        </div>
                    </div>
                </swiper-slide>      
            </swiper-container>
        </div>
    </div>
</template>

<script setup>
import { register } from 'swiper/element/bundle';

onMounted(()=>{
    register()
    const swiperEl = document.querySelector('swiper-container') ;

// swiper parameters
const swiperParams = {
  slidesPerView: 1,
  loop: true,
  autoplay: true,
  breakpoints: {
    760: {
      slidesPerView: 2,
    },
    // 1024: {
    //   slidesPerView: 3,
    // },
  },
  on: {
    init() {
      // ...
    },
  },
};

// now we need to assign all parameters to Swiper element
Object.assign(swiperEl, swiperParams);

// and now initialize it
swiperEl.initialize();
})
</script>

<style scoped>

</style>