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
          About Us
        </h2>
      </div>
    </div>

    <what-are-we />
    <div class="font-thin block my-10 py-10 text-lg ">
      <p class="md:px-20">
        In the heart of our Digital Agency beats the pulse of collaboration and
        ingenuity. We thrive on understanding the unique essence of each
        client's vision, tailoring our approach to suit diverse needs. From
        conceptualization to execution, our journey is marked by a commitment to
        precision and a relentless pursuit of excellence. Whether crafting
        visually stunning websites, developing innovative applications, or
        devising strategic digital marketing campaigns, we harness the power of
        technology to elevate brands and leave an indelible mark on the digital
        landscape. At our Digital Agency, we don't just create; we orchestrate a
        symphony of ideas, weaving a tapestry that defines the essence of our
        clients' aspirations.
      </p>
      <br />
      <p class="md:mx-20">
        Beyond the realm of code and design, our Digital Agency is a community
        of forward-thinkers and creators who are passionate about making a
        difference. We believe that the marriage of innovation and imagination
        is the catalyst for transformative experiences. With a commitment to
        staying ahead of industry trends, we embrace the challenge of navigating
        the ever-evolving digital ecosystem. As a Digital Agency, we stand as a
        beacon of inspiration, dedicated to shaping the future of digital
        possibilities and ensuring that every idea finds its vibrant expression
        in the digital realm.
      </p>
    </div>
    <div class="bg-slate-200 my-10 py-10">
      <div class="lg:max-w-[80%] mx-auto">
        <h1 class="text-center text-3xl font-bold mb-10" data-aos="fade-down">Meet Our Team</h1>
        <div class="grid lg:grid-cols-3 sm:grid-cols-2 ">
          <div data-aos="fade-up">
            <img src="/img/team/ceo.jpg" alt="Image of chijison tech ceo" class="w-[300px] h-[300px] rounded object-cover mx-auto">
            <h1 class="text-lg font-bold text-center mt-3">Okigwe Alfred Chijison</h1>
            <p class="text-center font-semibold text-slate-500 text-sm italic">chief executive officer</p>
          </div>
          <div data-aos="fade-up">
            <img src="/img/team/fsd.jpg" alt="Image of chijison tech ceo" class="w-[300px] h-[300px] rounded object-cover mx-auto">
            <h1 class="text-lg font-bold text-center mt-3">Theophane Chibuike</h1>
            <p class="text-center font-semibold text-slate-500 text-sm italic">Director</p>
          </div>
          <div data-aos="fade-up">
            <img src="/img/team/fsd.jpg" alt="Image of chijison tech ceo" class="w-[300px] h-[300px] rounded object-cover mx-auto">
            <h1 class="text-lg font-bold text-center mt-3">Ebube Ireneaus</h1>
            <p class="text-center font-semibold text-slate-500 text-sm italic">Project Manager</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
