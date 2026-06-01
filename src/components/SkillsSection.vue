<script setup>
import { Icon } from "@iconify/vue";

const skills = [
  { name: "HTML5", icon: "vscode-icons:file-type-html" },
  { name: "CSS3", icon: "vscode-icons:file-type-css" },
  { name: "JavaScript", icon: "logos:javascript" },
  { name: "Vue", icon: "logos:vue" },
  { name: "PHP", icon: "logos:php" },
  { name: "Laravel", icon: "logos:laravel" },
  { name: "Flutter", icon: "logos:flutter" },
  { name: "MySQL", icon: "logos:mysql" },
  { name: "Git", icon: "mdi:git" },
  { name: "GitHub", icon: "mdi:github" },
];
</script>

<template>
  <section id="skills" class="py-28 px-6 bg-slate-950">
    <div data-aos="fade-up" data-aos-duration="1000" class="max-w-7xl mx-auto">
      <!-- Heading -->
      <div class="mb-16">
        <p class="text-blue-400 text-lg mb-3">Skills</p>

        <h2 class="text-4xl md:text-5xl font-bold">Technologies I work with</h2>
      </div>

      <!-- Horizontal Scroll -->
      <div data-aos="fade-up" data-aos-duration="1100" class="marquee">
        <div class="marquee-content">
          <div
            v-for="skill in [...skills, ...skills]"
            :key="skill.name + Math.random()"
            class="min-w-[160px] bg-slate-900 border border-slate-800 rounded-3xl p-6 flex flex-col items-center hover:border-blue-500 transition duration-300 scrollbar-hide"
          >
            <!-- Icon -->
            <Icon :icon="skill.icon" class="text-6xl mb-5" />

            <!-- Name -->
            <h3 class="font-semibold text-lg mb-2">
              {{ skill.name }}
            </h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
