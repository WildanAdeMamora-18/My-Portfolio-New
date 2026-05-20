<script setup>
import { Icon } from "@iconify/vue";
</script>

<template>
  <section id="contact" class="py-28 px-6 bg-slate-950" data-aos="fade-up">
    <div class="max-w-7xl mx-auto">
      <!-- Heading -->
      <div class="mb-16">
        <p class="text-blue-400 text-lg mb-3">Contact</p>

        <h2 class="text-4xl md:text-5xl font-bold">Let's work together</h2>
      </div>

      <!-- Contact Card -->
      <div class="relative bg-slate-900 border border-slate-800 rounded-3xl p-10 overflow-hidden">
        <!-- Glow -->
        <div class="absolute inset-0 bg-blue-500 opacity-10 blur-3xl"></div>

        <div class="relative z-10 grid md:grid-cols-2 gap-12 items-center">
          <!-- Left -->
          <div>
            <h3 class="text-3xl font-bold mb-6">Have a project idea?</h3>

            <p class="text-slate-400 leading-relaxed mb-8">
              I'm open to freelance opportunities, collaborations, and interesting projects. Feel
              free to reach out anytime.
            </p>

            <a
              href="#contact" class="bg-blue-600 hover:bg-blue-700 transition px-7 py-4 rounded-2xl font-semibold"
            >
              Contact Me
            </a>
          </div>

          <!-- Right -->
          <div class="space-y-5">
            <!-- Email -->
            <div
              class="flex items-center gap-4 bg-slate-950 border border-slate-800 rounded-2xl p-5 hover:border-blue-500 transition"
            >
              <div class="w-14 h-14 rounded-2xl bg-blue-500/20 flex items-center justify-center">
                <Icon icon="mdi:email-outline" class="text-3xl text-blue-400" />
              </div>

              <div>
                <p class="text-slate-400 text-sm">Email</p>

                <h4 class="font-semibold">wildanademamora817@gmail.com</h4>
              </div>
            </div>

            <!-- GitHub -->
            <div
              class="flex items-center gap-4 bg-slate-950 border border-slate-800 rounded-2xl p-5 hover:border-blue-500 transition"
            >
              <div class="w-14 h-14 rounded-2xl bg-blue-500/20 flex items-center justify-center">
                <Icon icon="mdi:github" class="text-3xl text-blue-400" />
              </div>

              <div>
                <p class="text-slate-400 text-sm">GitHub</p>

                <h4 class="font-semibold">github.com/WildanAdeMamora-18</h4>
              </div>
            </div>

            <!-- LinkedIn -->
            <div
              class="flex items-center gap-4 bg-slate-950 border border-slate-800 rounded-2xl p-5 hover:border-blue-500 transition"
            >
              <div class="w-14 h-14 rounded-2xl bg-blue-500/20 flex items-center justify-center">
                <Icon icon="mdi:linkedin" class="text-3xl text-blue-400" />
              </div>

              <div>
                <p class="text-slate-400 text-sm">LinkedIn</p>

                <h4 class="font-semibold">linkedin.com/in/wildan-ade-mamora/</h4>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
