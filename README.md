<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ganesh savale | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: '#10b981'
          }
        }
      }
    };
  </script>
</head>
<body class="bg-slate-950 text-slate-100">
  <div class="min-h-screen bg-[radial-gradient(circle_at_top,_rgba(16,185,129,0.18),_transparent_30%),linear-gradient(180deg,#020617_0%,#0f172a_100%)]">
    <nav class="mx-auto flex max-w-6xl items-center justify-between px-6 py-6 text-slate-200">
      <a href="#home" class="text-2xl font-semibold text-brand">Ganesh savale</a>
      <div class="hidden items-center gap-8 md:flex">
        <a href="#about" class="hover:text-white">About</a>
        <a href="#skills" class="hover:text-white">Skills</a>
        <a href="#projects" class="hover:text-white">Projects</a>
        <a href="#contact" class="hover:text-white">Contact</a>
      </div>
      <button id="themeToggle" class="inline-flex items-center gap-2 rounded-full border border-slate-700 bg-slate-900/80 px-4 py-2 text-sm text-slate-200 transition hover:border-brand hover:text-brand">
        <span id="themeIcon" class="text-brand">🌙</span>
        <span id="themeText">Dark mode</span>
      </button>
    </nav>

    <header id="home" class="mx-auto max-w-6xl px-6 py-20 text-center">
      <p class="text-sm uppercase tracking-[0.4em] text-brand/80">Web developer & UI enthusiast</p>
      <h1 class="mt-6 text-5xl font-bold tracking-tight text-white sm:text-6xl">
        Hello, I’m <span class="text-brand">Ganesh</span>.
      </h1>
      <p class="mx-auto mt-6 max-w-2xl text-lg leading-8 text-slate-300">
        I build responsive, modern websites and user-friendly web applications using HTML, CSS, JavaScript,
        React, Tailwind CSS, and Node.js.
      </p>
      <div class="mt-10 flex flex-col items-center justify-center gap-4 sm:flex-row">
        <a href="#projects" class="rounded-full bg-brand px-8 py-3 text-sm font-semibold text-slate-950 shadow-lg shadow-brand/20 transition hover:bg-emerald-400">See Projects</a>
        <a href="#contact" class="rounded-full border border-slate-700 px-8 py-3 text-sm text-slate-200 transition hover:border-brand hover:text-brand">Get in touch</a>
      </div>
    </header>
  </div>

  <main class="mx-auto max-w-6xl px-6 pb-20">
    <section id="about" class="rounded-3xl border border-slate-800 bg-slate-900/90 p-8 shadow-xl shadow-slate-900/40 backdrop-blur-sm sm:p-12">
      <div class="flex flex-col gap-8 lg:flex-row lg:items-center">
        <div class="space-y-4 lg:w-2/3">
          <p class="text-xl font-semibold text-brand">About me</p>
          <h2 class="text-3xl font-bold text-white">A focused front-end developer with a love for clean UI.</h2>
          <p class="max-w-2xl leading-8 text-slate-300">
            I enjoy transforming ideas into fast, polished websites. I specialize in responsive front-end development,
            user interface design, and web performance optimization.
          </p>
          <div class="grid gap-4 sm:grid-cols-2">
            <div class="rounded-2xl bg-slate-800/80 p-5">
              <p class="text-sm uppercase tracking-[0.24em] text-slate-400">Experience</p>
              <p class="mt-3 text-xl font-semibold text-white">1+ years building web apps</p>
            </div>
            <div class="rounded-2xl bg-slate-800/80 p-5">
              <p class="text-sm uppercase tracking-[0.24em] text-slate-400">Focus</p>
              <p class="mt-3 text-xl font-semibold text-white">Modern JavaScript & Tailwind</p>
            </div>
          </div>
        </div>
        <div class="rounded-3xl border border-slate-800 bg-slate-950/95 p-6 text-slate-200 shadow-xl shadow-slate-900/40 lg:w-1/3">
          <p class="text-sm uppercase tracking-[0.24em] text-slate-500">Contact</p>
          <p class="mt-4 text-lg font-semibold text-white">Let’s build your next project.</p>
          <div class="mt-6 space-y-4 text-sm text-slate-300">
            <div><span class="font-semibold text-slate-100">Email:</span> ganesh@example.com</div>
            <div><span class="font-semibold text-slate-100">Location:</span> Pune, India</div>
            <div><span class="font-semibold text-slate-100">Role:</span> Frontend Developer</div>
          </div>
        </div>
      </div>
    </section>

    <section id="skills" class="mt-12 space-y-8">
      <div class="flex flex-col gap-4 md:flex-row md:items-center md:justify-between">
        <div>
          <p class="text-sm uppercase tracking-[0.32em] text-brand/80">Skills</p>
          <h3 class="mt-3 text-3xl font-bold text-white">What I work with</h3>
        </div>
      </div>
      <div class="grid gap-6 sm:grid-cols-2 xl:grid-cols-3">
        <div class="rounded-3xl border border-slate-800 bg-slate-900/90 p-6">
          <p class="text-lg font-semibold text-white">Frontend</p>
          <ul class="mt-5 space-y-3 text-slate-300">
            <li>HTML5 · CSS3 · Tailwind CSS</li>
            <li>JavaScript · TypeScript</li>
            <li>React · Next.js</li>
          </ul>
        </div>
        <div class="rounded-3xl border border-slate-800 bg-slate-900/90 p-6">
          <p class="text-lg font-semibold text-white">Backend</p>
          <ul class="mt-5 space-y-3 text-slate-300">
            <li>Node.js · Express</li>
            <li>MongoDB · PostgreSQL</li>
            <li>REST APIs · Authentication</li>
          </ul>
        </div>
        <div class="rounded-3xl border border-slate-800 bg-slate-900/90 p-6">
          <p class="text-lg font-semibold text-white">Tools</p>
          <ul class="mt-5 space-y-3 text-slate-300">
            <li>Git · GitHub</li>
            <li>Figma · VS Code</li>
            <li>Vercel · Netlify</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="projects" class="mt-16">
      <div class="flex flex-col gap-4 sm:flex-row sm:items-end sm:justify-between">
        <div>
          <p class="text-sm uppercase tracking-[0.32em] text-brand/80">Projects</p>
          <h3 class="mt-3 text-3xl font-bold text-white">Selected work</h3>
        </div>
      </div>
      <div class="mt-8 grid gap-6 lg:grid-cols-2">
        <article class="rounded-3xl border border-slate-800 bg-slate-900/90 p-6 shadow-lg shadow-slate-900/20">
          <p class="text-sm uppercase tracking-[0.24em] text-brand/80">UI Design</p>
          <h4 class="mt-4 text-2xl font-semibold text-white">Portfolio Website</h4>
          <p class="mt-4 leading-7 text-slate-300">A responsive personal brand website built with Tailwind CSS and animated sections to showcase experience, skills, and contact details.</p>
          <div class="mt-6 flex flex-wrap gap-2 text-xs text-slate-400">
            <span class="rounded-full border border-slate-700 px-3 py-1">Tailwind</span>
            <span class="rounded-full border border-slate-700 px-3 py-1">HTML</span>
            <span class="rounded-full border border-slate-700 px-3 py-1">JavaScript</span>
          </div>
        </article>
        <article class="rounded-3xl border border-slate-800 bg-slate-900/90 p-6 shadow-lg shadow-slate-900/20">
          <p class="text-sm uppercase tracking-[0.24em] text-brand/80">Web App</p>
          <h4 class="mt-4 text-2xl font-semibold text-white">Task Manager</h4>
          <p class="mt-4 leading-7 text-slate-300">A task management dashboard that tracks work items, deadlines, and progress using a clean, accessible interface.</p>
          <div class="mt-6 flex flex-wrap gap-2 text-xs text-slate-400">
            <span class="rounded-full border border-slate-700 px-3 py-1">React</span>
            <span class="rounded-full border border-slate-700 px-3 py-1">Node.js</span>
            <span class="rounded-full border border-slate-700 px-3 py-1">API</span>
          </div>
        </article>
      </div>
    </section>

    <section id="contact" class="mt-16 rounded-3xl border border-slate-800 bg-slate-900/90 p-8 text-slate-100 shadow-xl shadow-slate-900/30 sm:p-10">
      <div class="flex flex-col gap-6 sm:flex-row sm:items-center sm:justify-between">
        <div>
          <p class="text-sm uppercase tracking-[0.32em] text-brand/80">Reach out</p>
          <h3 class="mt-3 text-3xl font-bold text-white">Ready to work together?</h3>
          <p class="mt-4 max-w-2xl leading-8 text-slate-300">Send a message and let’s discuss your next project. I’m available for freelance and full-time opportunities.</p>
        </div>
        <a href="mailto:akash@example.com" class="inline-flex rounded-full bg-brand px-8 py-4 text-sm font-semibold text-slate-950 transition hover:bg-emerald-400">Email me</a>
      </div>
    </section>
  </main>

  <footer class="border-t border-slate-800 bg-slate-950 py-6 text-center text-slate-500">
    © 2026 Ganesh savale. Built with Tailwind CSS.
  </footer>

  <script src="javasscript.js"></script>
</body>
</html>
