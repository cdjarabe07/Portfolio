# portfolio-djarabe
<!doctype html>
<html lang="fr">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CALEB DJARABÉ — Data Scientist Junior</title>
    <meta
      name="description"
      content="Portfolio de CALEB DJARABÉ — Data Scientist Junior à Dakar, Sénégal."
    />
    <!-- Inter font -->
    <link
      rel="preconnect"
      href="https://fonts.googleapis.com"
    />
    <link
      rel="preconnect"
      href="https://fonts.gstatic.com"
      crossorigin
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap"
      rel="stylesheet"
    />
    <!-- Tailwind CSS (CDN) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            boxShadow: {
              soft: "0 10px 30px rgba(0,0,0,.35)",
            },
          },
        },
      };
    </script>
    <style>
      /* Slightly smoother font rendering on dark backgrounds */
      html {
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
      }
      body {
        font-family: "Inter", system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
          sans-serif;
      }
    </style>
  </head>
  <body class="min-h-screen bg-slate-950 text-slate-200 selection:bg-sky-500/30">
    <!-- Background glow -->
    <div aria-hidden="true" class="pointer-events-none fixed inset-0">
      <div
        class="absolute -top-40 left-1/2 h-[520px] w-[520px] -translate-x-1/2 rounded-full bg-gradient-to-b from-sky-500/12 to-fuchsia-500/0 blur-3xl"
      ></div>
      <div
        class="absolute -bottom-40 right-0 h-[520px] w-[520px] rounded-full bg-gradient-to-t from-emerald-500/10 to-sky-500/0 blur-3xl"
      ></div>
    </div>
    <!-- Sticky navigation -->
    <header
      class="sticky top-0 z-30 border-b border-slate-800/80 bg-slate-950/80 backdrop-blur"
    >
      <div
        class="mx-auto flex h-14 w-full max-w-6xl items-center justify-between px-4 text-sm sm:px-6 lg:px-8"
      >
        <div class="flex items-center gap-2">
          <span class="h-2 w-2 rounded-full bg-emerald-400/80"></span>
          <span class="text-xs font-semibold uppercase tracking-[0.2em] text-slate-400">
            CALEB DJARABÉ
          </span>
        </div>
        <nav class="hidden items-center gap-6 text-xs font-medium text-slate-300 sm:flex">
          <a href="#apropos" class="hover:text-slate-100">À propos</a>
          <a href="#projets" class="hover:text-slate-100">Mes Projets Data</a>
          <a href="#competences" class="hover:text-slate-100">Compétences</a>
          <a href="#cv" class="hover:text-slate-100">Références & CV</a>
        </nav>
        <a
          href="https://github.com/cdjarabe07/portfolio-caleb/raw/main/CV_Caleb.pdf"
          class="rounded-full bg-sky-500/90 px-3 py-1.5 text-xs font-semibold text-slate-950 shadow-soft transition hover:bg-sky-400"
        >
          Télécharger mon CV
        </a>
      </div>
    </header>
    <main class="relative mx-auto w-full max-w-6xl px-4 py-10 sm:px-6 lg:px-8">
      <!-- En-tête & Profil -->
      <header class="mb-10" id="apropos">
        <div class="flex flex-col gap-6 sm:flex-row sm:items-end sm:justify-between">
          <div>
            <p class="text-xs font-medium uppercase tracking-[0.2em] text-slate-400">
              Portfolio
            </p>
            <h1 class="mt-3 text-3xl font-semibold tracking-tight text-slate-50 sm:text-4xl">
              CALEB DJARABÉ
            </h1>
            <p class="mt-2 text-base font-medium text-slate-200">Data Scientist Junior</p>
            <div class="mt-4 flex flex-col gap-1 text-sm text-slate-300">
              <p class="text-slate-300">Dakar, Sénégal</p>
              <p class="text-slate-300">
                <a class="underline decoration-slate-600 underline-offset-4 hover:text-slate-100" href="mailto:cdjarabejw@gmail.com"
                  >cdjarabejw@gmail.com</a
                >
                <span class="text-slate-500">|</span>
                <a class="underline decoration-slate-600 underline-offset-4 hover:text-slate-100" href="tel:+221774375522"
                  >(+221) 77 437 55 22</a
                >
              </p>
            </div>
          </div>
          <div class="flex items-center gap-3">
            <a
              href="https://github.com/cdjarabe07/portfolio-caleb/raw/main/CV_Caleb.pdf"
              class="hidden rounded-full border border-sky-500/70 bg-sky-500/10 px-4 py-2 text-sm font-medium text-sky-300 shadow-soft backdrop-blur transition hover:border-sky-400 hover:text-sky-200 sm:inline-flex"
            >
              Télécharger mon CV
            </a>
            <a
              class="rounded-full border border-slate-700/70 bg-slate-900/40 px-4 py-2 text-sm text-slate-300 shadow-soft backdrop-blur transition hover:border-slate-600/80 hover:text-slate-100"
              href="https://github.com/cdjarabe07"
              target="_blank"
              rel="noreferrer"
              aria-label="GitHub"
              >GitHub</a
            >
            <a
              class="rounded-full border border-slate-700/70 bg-slate-900/40 px-4 py-2 text-sm text-slate-300 shadow-soft backdrop-blur transition hover:border-slate-600/80 hover:text-slate-100"
              href="https://www.linkedin.com/in/cdjarabe07/"
              target="_blank"
              rel="noreferrer"
              aria-label="LinkedIn"
              >LinkedIn</a
            >
          </div>
        </div>
      </header>
      <!-- Synthèse professionnelle -->
      <section
        aria-label="Synthèse Professionnelle"
        class="relative mb-8 overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/30 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40"
      >
        <div class="p-6">
          <h2 class="text-lg font-semibold tracking-tight text-slate-50">
            Synthèse Professionnelle
          </h2>
          <p class="mt-3 text-sm leading-relaxed text-slate-300">
            Data Scientist junior, issu d'une formation en économie appliquée, avec une
            spécialisation progressive en analyse de données et modélisation prédictive. Bonne
            maîtrise des fondamentaux statistiques et de Python pour l'exploration et
            l'interprétation des données.
          </p>
        </div>
      </section>
      <!-- Mes Projets Data -->
      <section
        id="projets"
        aria-label="Mes Projets Data"
        class="group relative mb-10 overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-900/60 to-slate-950 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-blue-500/80"
      >
        <div
          aria-hidden="true"
          class="pointer-events-none absolute inset-0 opacity-0 transition duration-500 group-hover:opacity-100"
        >
          <div
            class="absolute -top-24 -left-24 h-64 w-64 rounded-full bg-gradient-to-br from-sky-500/18 to-fuchsia-500/0 blur-2xl"
          ></div>
          <div
            class="absolute -bottom-24 -right-24 h-64 w-64 rounded-full bg-gradient-to-tr from-emerald-500/14 to-sky-500/0 blur-2xl"
          ></div>
        </div>
        <div class="relative p-6">
          <div class="flex flex-col gap-2 sm:flex-row sm:items-baseline sm:justify-between">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">
              Mes Projets Data
            </h2>
            <p class="text-sm text-slate-400">
              Une sélection de projets autour de la Data Science.
            </p>
          </div>
          <div class="mt-5 grid grid-cols-1 gap-4 lg:grid-cols-2">
            <!-- Projet: ScoutIQ -->
            <article
              class="relative overflow-hidden rounded-2xl border border-slate-800/80 bg-gradient-to-b from-slate-900/60 to-slate-950 p-5 transition will-change-transform hover:-translate-y-0.5 hover:border-blue-500/80"
            >
              <div class="flex items-start justify-between gap-4">
                <h3 class="text-base font-semibold tracking-tight text-slate-50">
                  ScoutIQ
                </h3>
                <span
                  class="inline-flex items-center rounded-full border border-slate-700/70 bg-slate-950/40 px-2 py-1 text-[11px] font-medium text-slate-300"
                  >Streamlit</span
                >
              </div>
              <div class="mt-3 flex flex-wrap gap-2">
                <span
                  class="rounded-full border border-slate-700/70 bg-slate-950/40 px-3 py-1 text-xs text-slate-300"
                  >Python</span
                >
                <span
                  class="rounded-full border border-slate-700/70 bg-slate-950/40 px-3 py-1 text-xs text-slate-300"
                  >Pandas</span
                >
                <span
                  class="rounded-full border border-slate-700/70 bg-slate-950/40 px-3 py-1 text-xs text-slate-300"
                  >Machine Learning</span
                >
              </div>
              <p class="mt-4 text-sm leading-relaxed text-slate-300">
                Application interactive pour explorer des données, tester des hypothèses et présenter
                des résultats de manière claire (EDA + insights), avec une interface légère pensée
                pour le reporting.
              </p>
              <div class="mt-5 flex flex-col gap-3 sm:flex-row">
                <a
                  href="https://github.com/cdjarabe07/ScoutIQ"
                  target="_blank"
                  rel="noreferrer"
                  class="inline-flex w-full items-center justify-center rounded-xl border border-sky-500/80 bg-slate-950/40 px-4 py-2.5 text-sm font-medium text-sky-300 shadow-soft transition hover:border-blue-500/90 hover:bg-slate-900/60"
                >
                  Voir le Code
                </a>
                <a
                  href="https://scoutiq-cdjarabe.streamlit.app/"
                  target="_blank"
                  rel="noreferrer"
                  class="inline-flex w-full items-center justify-center rounded-xl bg-gradient-to-r from-sky-500/90 to-blue-500/90 px-4 py-2.5 text-sm font-semibold text-slate-950 shadow-soft transition hover:from-sky-400 hover:to-blue-400"
                >
                  Lancer l’Application
                </a>
              </div>
            </article>
            <!-- Projet: Analyseur de Sentiment Reddit (Coming Soon) -->
            <article
              class="relative overflow-hidden rounded-2xl border border-slate-800/80 bg-gradient-to-b from-slate-900/50 to-slate-950 p-5 transition will-change-transform hover:-translate-y-0.5 hover:border-blue-500/80"
            >
              <div class="flex items-start justify-between gap-4">
                <h3 class="text-base font-semibold tracking-tight text-slate-50">
                  Analyseur de Sentiment Reddit
                </h3>
                <span
                  class="inline-flex items-center rounded-full border border-slate-700/70 bg-slate-950/35 px-2 py-1 text-[11px] font-medium text-slate-300"
                  >Coming Soon</span
                >
              </div>
              <div class="mt-3 flex flex-wrap gap-2">
                <span
                  class="rounded-full border border-slate-700/70 bg-slate-950/35 px-3 py-1 text-xs text-slate-300"
                  >Python</span
                >
                <span
                  class="rounded-full border border-slate-700/70 bg-slate-950/35 px-3 py-1 text-xs text-slate-300"
                  >NLP</span
                >
                <span
                  class="rounded-full border border-slate-700/70 bg-slate-950/35 px-3 py-1 text-xs text-slate-300"
                  >Visualisation</span
                >
              </div>
              <p class="mt-4 text-sm leading-relaxed text-slate-300">
                Projet en cours autour de l’analyse de sentiment sur des discussions Reddit : collecte,
                nettoyage, features et modèles de classification pour suivre des tendances
                d’opinion.
              </p>
              <div class="mt-5 flex flex-col gap-3 sm:flex-row">
                <span
                  class="inline-flex w-full cursor-not-allowed items-center justify-center rounded-xl border border-slate-800 bg-slate-950/30 px-4 py-2.5 text-sm font-medium text-slate-500"
                  >Voir le Code</span
                >
                <span
                  class="inline-flex w-full cursor-not-allowed items-center justify-center rounded-xl border border-slate-800 bg-slate-950/20 px-4 py-2.5 text-sm font-semibold text-slate-500"
                  >Démo Bientôt Disponible</span
                >
              </div>
            </article>
          </div>
        </div>
      </section>
      <div class="grid grid-cols-1 gap-5 lg:grid-cols-3">
        <!-- Compétences -->
        <section
          aria-label="Compétences"
          id="competences"
          class="relative overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/30 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40 lg:col-span-3"
        >
          <div class="p-6">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">Compétences</h2>
            <div class="mt-4 grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-3">
              <div class="rounded-xl border border-slate-800/70 bg-slate-950/10 p-4">
                <p class="text-sm font-semibold text-slate-100">Data Science & Analyse</p>
                <p class="mt-2 text-sm text-slate-300">
                  EDA, nettoyage des données, statistiques appliquées.
                </p>
              </div>
              <div class="rounded-xl border border-slate-800/70 bg-slate-950/10 p-4">
                <p class="text-sm font-semibold text-slate-100">Machine Learning (junior)</p>
                <p class="mt-2 text-sm text-slate-300">
                  régression, classification, évaluation de modèles.
                </p>
              </div>
              <div class="rounded-xl border border-slate-800/70 bg-slate-950/10 p-4">
                <p class="text-sm font-semibold text-slate-100">Programmation & Outils</p>
                <p class="mt-2 text-sm text-slate-300">Python, Pandas, NumPy, SQL.</p>
              </div>
              <div class="rounded-xl border border-slate-800/70 bg-slate-950/10 p-4">
                <p class="text-sm font-semibold text-slate-100">Data Visualisation & Reporting</p>
                <p class="mt-2 text-sm text-slate-300">
                  Google Sheets, Power BI, Tableau.
                </p>
              </div>
              <div class="rounded-xl border border-slate-800/70 bg-slate-950/10 p-4 md:col-span-2 lg:col-span-2">
                <p class="text-sm font-semibold text-slate-100">Finance & Métier</p>
                <p class="mt-2 text-sm text-slate-300">
                  analyse financière, gestion des risques bancaires, données transactionnelles.
                </p>
              </div>
            </div>
          </div>
        </section>
        <!-- Formation -->
        <section
          aria-label="Formation"
          class="relative overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/25 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40 lg:col-span-2"
        >
          <div class="p-6">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">Formation</h2>
            <div class="mt-4 rounded-xl border border-slate-800/70 bg-slate-950/10 p-4">
              <p class="text-sm font-semibold text-slate-100">
                Licence : Économie Appliquée
              </p>
              <p class="mt-1 text-sm text-slate-300">
                Université St. Charles Lwanga — Sarh, Tchad
              </p>
              <p class="mt-1 text-sm text-slate-400">Novembre 2020 – Septembre 2023</p>
            </div>
          </div>
        </section>
        <!-- Certificats -->
        <section
          aria-label="Certificats"
          class="relative overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/25 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40"
        >
          <div class="p-6">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">Certificats</h2>
            <ul class="mt-3 space-y-2 text-sm leading-relaxed text-slate-300">
              <li class="rounded-lg border border-slate-800/70 bg-slate-950/10 px-3 py-2">
                Certificat Professionnel d'Analyse de Données, Google (Coursera).
              </li>
              <li class="rounded-lg border border-slate-800/70 bg-slate-950/10 px-3 py-2">
                Certificat Professionnel en Data Science, GoMyCode Sénégal.
              </li>
              <li class="rounded-lg border border-slate-800/70 bg-slate-950/10 px-3 py-2">
                Certificat de Réussite en Intelligence Économique, ITC e-learning.
              </li>
            </ul>
          </div>
        </section>
        <!-- Langues -->
        <section
          aria-label="Langues"
          class="relative overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/25 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40"
        >
          <div class="p-6">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">Langues</h2>
            <ul class="mt-3 space-y-2 text-sm text-slate-300">
              <li class="flex items-center justify-between gap-3">
                <span>Français</span><span class="text-slate-400">Courant</span>
              </li>
              <li class="flex items-center justify-between gap-3">
                <span>Anglais</span><span class="text-slate-400">B1.2</span>
              </li>
            </ul>
          </div>
        </section>
        <!-- Centres d’intérêt -->
        <section
          aria-label="Centres d’intérêt"
          class="relative overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/25 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40"
        >
          <div class="p-6">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">
              Centres d’intérêt
            </h2>
            <div class="mt-4 flex flex-wrap gap-2">
              <span class="rounded-full border border-slate-700/70 bg-slate-950/20 px-3 py-1 text-xs text-slate-300"
                >Arts créatifs</span
              >
              <span class="rounded-full border border-slate-700/70 bg-slate-950/20 px-3 py-1 text-xs text-slate-300"
                >Musique (folk acoustique)</span
              >
              <span class="rounded-full border border-slate-700/70 bg-slate-950/20 px-3 py-1 text-xs text-slate-300"
                >Basketball</span
              >
              <span class="rounded-full border border-slate-700/70 bg-slate-950/20 px-3 py-1 text-xs text-slate-300"
                >Voyage</span
              >
              <span class="rounded-full border border-slate-700/70 bg-slate-950/20 px-3 py-1 text-xs text-slate-300"
                >Natation</span
              >
            </div>
          </div>
        </section>
        <!-- Références -->
        <section
          aria-label="Références"
          id="cv"
          class="relative overflow-hidden rounded-2xl border border-slate-800 bg-gradient-to-b from-slate-800/25 to-slate-900/35 shadow-soft backdrop-blur transition will-change-transform hover:-translate-y-0.5 hover:border-slate-700/90 hover:bg-slate-900/40 lg:col-span-3"
        >
          <div class="p-6">
            <h2 class="text-lg font-semibold tracking-tight text-slate-50">Références & CV</h2>
            <p class="mt-3 text-sm leading-relaxed text-slate-300">
              Références et détails complets disponibles dans mon CV.
            </p>
          </div>
        </section>
      </div>
      <div class="mt-5 grid grid-cols-1 gap-5 lg:grid-cols-2">
      </div>
      <footer class="mt-12 border-t border-slate-800/80 pt-6">
        <div class="flex flex-col gap-2 text-sm text-slate-400 sm:flex-row sm:items-center sm:justify-between">
          <p>© <span id="year"></span> — CALEB DJARABÉ</p>
          <p class="text-slate-500">Minimal • Sombre • Tailwind</p>
        </div>
      </footer>
    </main>
    <script>
      document.getElementById("year").textContent = new Date().getFullYear();
    </script>
  </body>
</html>

