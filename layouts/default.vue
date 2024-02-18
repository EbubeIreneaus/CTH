<template>
  <div>
    <div class="absolute z-50 w-full font-sans">
      <header
        class="flex items-center justify-between px-7 relative bg-transparent w-full text-white/80"
      >
        <div>
          <img
            src="/img/cth_logo_l.png"
            class="size-28"
            alt="Chijison Tech hub logo"
          />
        </div>
        <nav class="">
          <i class="fa fa-bars block md:!hidden" @click="showNav = !showNav"></i>
          <ul
            class="md:flex md:flex-row absolute top-[100%] md:static flex-col justify-between items-center
             gap-5 *:font-semibold w-full left-0 *:py-2.5 *:block px-3 md:px-0 bg-slate-200
              md:bg-transparent text-black/80 md:text-white/80 max-h-[0px] md:max-h-full h-fit overflow-hidden
             transition-all duration-300 ease-in-out"
            :class="{'!max-h-[600px]':showNav}"
          >
            <NuxtLink to="/"><li>Home</li></NuxtLink>
            <NuxtLink to="/"><li>About</li></NuxtLink>
            <NuxtLink to="/"><li>Service</li></NuxtLink>
            <NuxtLink to="/"><li>Portfolio</li></NuxtLink>
            <NuxtLink to="/"><li>Contact</li></NuxtLink>
            <NuxtLink to="/"><li>Templates</li></NuxtLink>
            <NuxtLink to="/" class="my-3">
              <li>
                <ul
                  class="flex gap-7 items-center *:font-semibold md:hidden"
                >
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-facebook-f"></i></li
                  ></NuxtLink>
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-twitter"></i></li
                  ></NuxtLink>
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-linkedin"></i></li
                  ></NuxtLink>
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-instagram"></i></li
                  ></NuxtLink>
                </ul>
              </li>
            </NuxtLink>
          </ul>
        </nav>

        <ul
          class="md:flex justify-between items-center gap-5 *:font-semibold hidden"
        >
          <NuxtLink to="/"
            ><li><i class="fa-brands fa-facebook-f"></i></li
          ></NuxtLink>
          <NuxtLink to="/"
            ><li><i class="fa-brands fa-twitter"></i></li
          ></NuxtLink>
          <NuxtLink to="/"
            ><li><i class="fa-brands fa-linkedin"></i></li
          ></NuxtLink>
          <NuxtLink to="/"
            ><li><i class="fa-brands fa-instagram"></i></li
          ></NuxtLink>
        </ul>
      </header>
    </div>
    <slot></slot>

    <footer class="py-24 border md:px-16 bg-slate-900 text-white">
      <div class="grid lg:grid-cols-3 mg:grid-cols-2 gap-10">
        <div class="text-left">
          <h2 class="text-2xl font-bold mb-4">About Us</h2>
          <p class="font-thin">
            At our core, we are a dynamic Digital Agency committed to bringing ideas to life. With a fusion
             of innovation and creativity, we navigate the digital landscape, crafting compelling solutions
              that redefine online experiences. Our dedicated team is driven by a passion for excellence, 
              ensuring that every project reflects the unique essence of our clients and stands out in the 
              ever-evolving world of digital possibilities.
          </p>
          <ul
                  class="flex gap-7 items-center *:font-semibold my-7"
                >
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-facebook-f"></i></li
                  ></NuxtLink>
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-twitter"></i></li
                  ></NuxtLink>
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-linkedin"></i></li
                  ></NuxtLink>
                  <NuxtLink to="/"
                    ><li><i class="fa-brands fa-instagram"></i></li
                  ></NuxtLink>
                </ul>
        </div>

        <div>
          <h2 class="text-2xl font-bold">Contact Info</h2>
          <ul class="my-4">
            <li class="text-slate-500 italic">Address</li>
            <li class="font-bold">Fedral Housing Kubwa, Abuja Nigeria</li>
            <br>
            <li class="text-slate-500 italic">Telephone</li>
            <li class="font-bold">+234 806 198 2520, +234 808 541 9653</li>
            <br>
            <li class="text-slate-500 italic">Email</li>
            <li class="font-bold">service@chijisontechhub.com.ng</li>
          </ul>
        </div>

        <div>
          <h2 class="text-2xl font-bold mb-4">Quick Links</h2>
          <ul class="*:underline *:underline-offset-4 *:px-5 *:hover:text-white *:text-white/70 *:my-2">
            <li><nuxt-link to="/about">about</nuxt-link></li>
            <li><nuxt-link to="/portfolio">portfolio</nuxt-link></li>
            <li><nuxt-link to="/template">template</nuxt-link></li>
            <li><nuxt-link to="/contact">contact us</nuxt-link></li>
          </ul>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
const showNav = ref<boolean>(false)
</script>

<style scoped></style>
