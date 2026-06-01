<script setup>
import pmiAdminImage from '../assets/projects/pmi-admin.png'
import pmiPortalImage from '../assets/projects/pmi-portal.png'
import smartSchoolImage from '../assets/projects/smart-school-service.jpeg'
const projects = [
  {
    title: "SIMPADU PMI Admin Dashboard",
    description:
      "Admin dashboard system for managing PMI digital services, built using Laravel and Filament with CRUD functionality and modern backend architecture.",
    image: pmiAdminImage,
    tech: ["PHP", "Laravel", "Filament", "MySQL"],
    github: "https://github.com/WildanAdeMamora-18/simpadu-pmi.git",
  },
  {
    title: "SIMPADU PMI Web Portal",
    description:
      "Frontend website for PMI digital services with responsive interface and interactive user experience using HTML, CSS, and JavaScript.",
    image: pmiPortalImage,
    tech: ["HTML", "CSS", "JavaScript"],
    github: "",
  },
  {
    title: "Smart School Service System",
    description: "Fullstack web application for managing school facility borrowing and administration at SMP Negeri 19 Surabaya.",
    image: smartSchoolImage,
    tech: ["PHP", "Bootstrap", "JavaScript", "MySQL"],
    github: "https://github.com/WildanAdeMamora-18/smart-school-service.git",
  },
];
</script>

<template>
  <section id="projects" class="py-28 px-6 bg-slate-900">
    <div data-aos="fade-up" data-aos-duration="1000" class="max-w-7xl mx-auto">
      <!-- Heading -->
      <div class="mb-16">
        <p class="text-blue-400 text-lg mb-3">Projects</p>

        <h2 class="text-4xl md:text-5xl font-bold">Some things I've built</h2>
      </div>

      <!-- Projects Grid -->
      <div data-aos="zoom-in" data-aos-duration="1100" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
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
