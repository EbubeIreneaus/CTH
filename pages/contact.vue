<template>
  <div class="bg-slate-100">
    <div
      class="w-screen h-screen relative before:absolute before:w-full before:h-full before:top-0 before:left-0 before:bg-black/50 absolute:z-16"
    >
      <img
        src="~/assets/img/home-bg.jpg"
        alt=""
        class="w-full h-full object-cover"
      />
      <div
        class="absolute top-0 left-0 w-full h-full flex items-center justify-center z-30"
      >
        <h2
          class="text-5xl md:text-6xl font-extrabold text-white text-center px-2 animate__animated animate__fadeInLeft"
        >
          Contact Us
        </h2>
      </div>
    </div>

    <div class="grid lg:grid-cols-2 py-10 px-5">
      <form class="md:px-10">
        <div class="grid md:grid-cols-2 gap-4">
          <div class="w-full">
            <label for="">Name:</label>
            <input
              type="text"
              class="w-full outline-none border py-2 ps-2"
              placeholder="Full name"
            />
          </div>
          <div class="w-full">
            <label for="">Phone:</label>
            <input
              type="text"
              class="w-full outline-none border py-2 ps-2"
              placeholder="Phone"
            />
          </div>
        </div>
        <div class="mb-4">
          <label for="">Email:</label>
          <input
            type="email"
            class="w-full outline-none border py-2 ps-2"
            placeholder="Email"
          />
        </div>
        <div class="mb-4">
          <label for="">Message:</label>
          <textarea
            name=""
            id=""
            class="outline-none border w-full h-[200px] px-2"
            placeholder="message"
          ></textarea>
        </div>
        <div>
          <button
            class="w-fit block px-16 py-3 hover:bg-slate-300 border rounded"
          >
            send
          </button>
        </div>
      </form>
      <div>
        <div>
          <i class="fa fa-map-location"></i> &nbsp;
          <span class="text-xl font-thin">
            Fedral Capital Territory, Nigeria</span
          >
        </div>
        <div>
          <i class="fa-brands fa-whatsapp"></i> &nbsp;
          <span class="text-xl font-thin">
            Fedral C apital Territory, Nigeria</span
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
