<script setup>
import profileImage from "../assets/projects/profile.jpg";
const projects = [
  {
    title: "Personal Portfolio Website",
    description:
      "A responsive portfolio website built with Vue.js to showcase my projects and skills.",
    image: profileImage,
    tech: ["Vue.js", "Tailwind CSS", "JavaScript"],
    github: "",
  },
  {
    title: "E-commerce Store",
    description:
      "An online store built with Vue.js and Firebase for real-time database and authentication.",
    image: profileImage,
    tech: ["Vue.js", "Firebase", "Stripe API"],
    github: "",
  },
  {
    title: "Task Management App",
    description: "A task management application built with Vue.js and Vuex for state management.",
    image: profileImage,
    tech: ["Vue.js", "Vuex", "Axios"],
    github: "",
  },
];
</script>

<template>
  <section id="projects" class="py-28 px-6 bg-slate-900" data-aos="fade-up">
    <div class="max-w-7xl mx-auto">
      <!-- Heading -->
      <div class="mb-16">
        <p class="text-blue-400 text-lg mb-3">Projects</p>

        <h2 class="text-4xl md:text-5xl font-bold">Some things I've built</h2>
      </div>

      <!-- Projects Grid -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div
          v-for="project in projects"
          :key="project.title"
          data-aos="zoom-in"
          :data-aos-delay="100"
          class="group bg-slate-950 border border-transparent hover:border-blue-500 rounded-3xl overflow-hidden transition duration-300 hover:-translate-y-2 relative"
        >
          <!-- Glow -->
          <div
            class="absolute inset-0 bg-blue-500 opacity-0 blur-3xl group-hover:opacity-10 transition duration-300"
          ></div>

          <!-- Image -->
          <div class="overflow-hidden relative z-10">
            <img
              :src="project.image"
              :alt="project.title"
              class="w-full h-[220px] object-cover group-hover:scale-110 transition duration-500"
            />
          </div>

          <!-- Content -->
          <div class="p-6 relative z-10">
            <h3 class="text-2xl font-bold mb-4">{{ project.title }}</h3>

            <p class="text-slate-400 leading-relaxed mb-6">{{ project.description }}</p>

            <!-- Tech -->
            <div class="flex flex-wrap gap-3 mb-6">
              <span
                v-for="tech in project.tech"
                :key="tech"
                class="bg-slate-800 text-blue-400 text-sm px-4 py-2 rounded-full"
              >
                {{ tech }}
              </span>
            </div>

            <!-- GitHub Link -->
            <a
              :href="project.github"
              target="_blank"
              class="inline-flex items-center gap-2 text-blue-400 hover:text-blue-300 transition"
            >
              View Project →
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
