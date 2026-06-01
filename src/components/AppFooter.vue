<script setup>
import { Icon } from "@iconify/vue";
</script>

<template>
  <footer class="relative border-t border-slate-800 bg-slate-950 px-6 py-10 overflow-hidden">
    <!-- Glow -->
    <div class="absolute inset-0 bg-blue-500 opacity-5 blur-3xl"></div>

    <div
      class="relative z-10 max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6"
    >
      <!-- Left -->
      <div>
        <h2 class="text-2xl font-bold text-blue-500 mb-2">Mamoraaa.</h2>

        <p class="text-slate-400 text-sm">© 2026 Wildan Ade Mamora. All rights reserved.</p>
      </div>

      <!-- Right -->
      <div class="flex items-center gap-5">
        <a
          href="https://github.com/WildanAdeMamora-18"
          class="w-12 h-12 rounded-2xl bg-slate-900 border border-slate-800 flex items-center justify-center hover:border-blue-500 hover:-translate-y-1 transition"
        >
          <Icon icon="mdi:github" class="text-2xl text-blue-400" />
        </a>

        <a
          href="https://www.linkedin.com/in/wildan-ade-mamora/"
          class="w-12 h-12 rounded-2xl bg-slate-900 border border-slate-800 flex items-center justify-center hover:border-blue-500 hover:-translate-y-1 transition"
        >
          <Icon icon="mdi:linkedin" class="text-2xl text-blue-400" />
        </a>

        <a
          href="#"
          class="w-12 h-12 rounded-2xl bg-slate-900 border border-slate-800 flex items-center justify-center hover:border-blue-500 hover:-translate-y-1 transition"
        >
          <Icon icon="mdi:instagram" class="text-2xl text-blue-400" />
        </a>
      </div>
    </div>
  </footer>
</template>
