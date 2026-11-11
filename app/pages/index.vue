
<template>
  <div>
    <!-- Hero Section -->
    <section
      id="home"
      class="mx-auto flex min-h-[80vh] max-w-7xl items-center px-6 py-20"
    >
      <div class="max-w-3xl">
        <p class="mb-4 font-semibold text-emerald-400">
          HELLO, WELCOME TO MY PORTFOLIO
        </p>

        <h1 class="text-5xl font-bold tracking-tight sm:text-7xl">
          I'm Daniel Gian Salinas.
        </h1>

        <h2 class="mt-4 text-2xl font-semibold text-base-content/70 sm:text-3xl">
          Aspiring IT Professional & Developer
        </h2>

        <p class="mt-6 max-w-2xl leading-relaxed text-base-content/60">
          I am a Bachelor of Science in Information Technology student
          passionate about technology, programming, and building
          useful digital experiences.
        </p>

        <div class="mt-8 flex flex-wrap gap-4">
          <a href="#about" class="btn btn-primary">
            About Me
          </a>

          <a href="#contact" class="btn btn-outline">
            Contact Me
          </a>
        </div>
      </div>
    </section>

   <AboutSection />

<SkillsSection />

<TechStackSection />

<CertificationsSection />

  
<!-- Contact Section -->
<section id="contact" class="border-t border-base-300 px-6 py-20">
  <div class="mx-auto max-w-7xl text-center">

    <p class="mb-3 font-semibold text-emerald-400">
      LET'S CONNECT
    </p>

    <h2 class="text-3xl font-bold">
      Contact Me
    </h2>

    <p class="mx-auto mt-4 max-w-xl text-base-content/60">
      Feel free to connect with me through my professional platforms.
    </p>

    <div class="mt-10 flex flex-wrap justify-center gap-6">

      <a
        href="https://github.com/skipmakliw11"
        target="_blank"
        rel="noopener noreferrer"
        class="card w-full max-w-xs border border-base-300 bg-base-200 p-6 transition-all duration-300 hover:-translate-y-2 hover:border-primary hover:shadow-xl"
      >
        <div class="text-4xl">💻</div>
        <h3 class="mt-3 text-xl font-bold">GitHub</h3>
        <p class="mt-2 text-sm text-base-content/60">
          Check out my projects and repositories.
        </p>
        <span class="mt-4 font-semibold text-primary">
          Visit GitHub →
        </span>
      </a>

      <a
        href="https://www.linkedin.com/in/danielgiansalinas"
        target="_blank"
        rel="noopener noreferrer"
        class="card w-full max-w-xs border border-base-300 bg-base-200 p-6 transition-all duration-300 hover:-translate-y-2 hover:border-primary hover:shadow-xl"
      >
        <div class="text-4xl">💼</div>
        <h3 class="mt-3 text-xl font-bold">LinkedIn</h3>
        <p class="mt-2 text-sm text-base-content/60">
          Connect with me professionally.
        </p>
        <span class="mt-4 font-semibold text-primary">
          Visit LinkedIn →
        </span>
      </a>

    </div>
  </div>
</section>

  </div>
</template>
