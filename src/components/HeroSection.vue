<template>
  <section id="home" class="min-h-screen flex items-center justify-center px-6">
    <div class="max-w-7xl w-full grid grid-cols-2 gap-12 items-center">
      <!-- Section-Left -->
      <div data-aos="fade-up" data-aos-duration="1000">
        <p class="text-blue-400 mb-4 text-xl">Hello I'm</p>

        <h1 class="text-5xl md:text-7xl font-bold leading-tight mb-6">
          Wildan Ade <br /><span class="text-blue-500">Mamora</span>
        </h1>

        <p class="text-slate-400 text-lg leading-relaxed mb-8 max-w-lg">
          Informatics Engineering student passionate about web development and fullstack engineering, focused on building modern, responsive, and user-friendly digital experiences.
        </p>

        <div class="flex gap-4">
          <a
            href="#projects" class="bg-blue-600 hover:bg-blue-700 transition px-6 py-3 rounded-xl font-semibold"
          >
            View Projects
          </a>
          <a
            href="#contact" class="border border-slate-700 hover:border-blue-500 transition px-6 py-3 rounded-xl font-semibold"
          >
            Contact Me
          </a>
        </div>
      </div>

      <!-- Section-Right -->
      <div data-aos="zoom-in" data-aos-duration="1000" class="flex justify-center">
        <div
          class="w-[450px] h-[450px] rounded-full bg-gradient-to-br from-blue-500 to-blue-900 blur-3xl opacity-40 absolute"
        ></div>

        <div
          class="relative w-[400px] h-[400px] rounded-full border-4 border-blue-500 overflow-hidden shadow-2xl"
        >
          <img src="../assets/profile.jpg" alt="profile" class="w-full h-full object-cover" />
        </div>
      </div>
    </div>
  </section>
</template>
