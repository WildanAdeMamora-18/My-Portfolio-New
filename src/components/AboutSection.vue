<template>
  <section id="about" class="py-28 px-6 bg-slate-900" data-aos="fade-up">
    <div class="max-w-7xl mx-auto">
      <!-- Section Title -->
      <div class="mb-16">
        <p class="text-blue-400 mb-3 text-lg">About Me</p>

        <h2 class="text-4xl md:text-5xl font-bold">Get to know me</h2>
      </div>

      <!-- Content -->
      <div class="grid md:grid-cols-2 gap-16 items-center">
        <!-- Left -->
        <div>
          <p class="text-slate-400 text-lg leading-relaxed mb-8">
            I am an Informatics Engineering student who enjoys building modern web applications and
            learning new technologies. I focus on frontend development, cloud computing, and
            creating digital experiences that are clean, functional, and user friendly.
          </p>

          <!-- Info Cards -->
          <div class="grid grid-cols-2 gap-4">
            <!-- Card 1 -->
            <div class="bg-slate-800/70 border border-slate-700 rounded-2xl p-5">
              <h3 class="text-blue-400 text-sm mb-2">Education</h3>

              <p class="font-semibold">Informatics Engineering</p>
            </div>

            <!-- Card 2 -->
            <div class="bg-slate-800/70 border border-slate-700 rounded-2xl p-5">
              <h3 class="text-blue-400 text-sm mb-2">Semester</h3>

              <p class="font-semibold">6th Semester</p>
            </div>

            <!-- Card 3 -->
            <div class="bg-slate-800/70 border border-slate-700 rounded-2xl p-5">
              <h3 class="text-blue-400 text-sm mb-2">Focus</h3>

              <p class="font-semibold">Web Development</p>
            </div>

            <!-- Card 4 -->
            <div class="bg-slate-800/70 border border-slate-700 rounded-2xl p-5">
              <h3 class="text-blue-400 text-sm mb-2">Location</h3>

              <p class="font-semibold">Indonesia</p>
            </div>
          </div>
        </div>

        <!-- Right -->
        <div class="relative flex justify-center">
          <!-- Glow -->
          <div
            class="absolute w-[320px] h-[320px] bg-blue-500 opacity-20 blur-3xl rounded-full"
          ></div>

          <!-- Card -->
          <div
            class="relative bg-slate-800/70 border border-slate-700 rounded-3xl p-8 backdrop-blur-xl w-full max-w-md"
          >
            <div class="bg-slate-950 rounded-2xl p-6 border border-slate-700">
              <pre class="text-blue-400 text-sm overflow-x-auto">
const developer = {
  name: "Wildan",
  skills: [
    "Vue",
    "Laravel",
    "Flutter",
    "MySQL"
  ],
  passion: "Build modern apps"
}
              </pre>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
