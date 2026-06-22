---
title: "Bienvenue au Laboratoire DISP"
type: landing


sections:
  # ===========================================================================
  # RANGÉE 1 : L'PRÉSENTATION DU LABO (3 colonnes via HTML/Tailwind)
  # ===========================================================================
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 items-start my-8">
        <div class="space-y-6">
        <div>
        <h3 class="text-xl font-bold tracking-wide text-primary uppercase mb-3">Scientific Goal</h3>
        <p class="text-gray-600 dark:text-gray-300 text-justify">
        Improve the performance, the resilience, the agility of goods and services production systems and comprehensive supply chains, by simultaneously addressing their structural, decision-making, information-related and human-related dimensions.
        </p>
        </div>
        <div class="border-t pt-4">
        <h3 class="text-lg font-bold tracking-wide text-primary uppercase mb-2">Double Expertise</h3>
        <p class="font-medium text-gray-700 dark:text-gray-200">
        Industrial engineering &bull; Information technology
        </p>
        </div>
        </div>
        <div class="flex justify-center items-center h-full">
        <img src="/media/venn_en_2021.png" alt="DISP Lab" class="max-w-full h-auto rounded-lg shadow-sm">
        </div>
        <div class="space-y-6">
        <div>
        <h3 class="text-xl font-bold tracking-wide text-primary uppercase mb-3">Key Figures</h3>
        <ul class="space-y-2 text-gray-600 dark:text-gray-300">
        <li><strong>30</strong> lecturers and researchers</li>
        <li><strong>26</strong> PhD students</li>
        <li><strong>3</strong> technico-administrative staff</li>
        <li><strong>15</strong> visiting scholars or interns every year</li>
        </ul>
        <a href="/membres/" class="inline-block mt-3 text-sm font-semibold text-blue-600 hover:underline">See members &rarr;</a>
        </div>
        <div class="border-t pt-4">
        <h3 class="text-lg font-bold tracking-wide text-primary uppercase mb-2">Get to know more</h3>
        <a href="/documents/DISP_plaquette_en.pdf" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.5rem 1rem; background-color: #0070f3; color: white; border-radius: 0.375rem; font-size: 0.875rem; font-medium; text-decoration: none;">
        Download our brochure
        </a>
        </div>
        </div>
        </div>
    design:
      spacing:
        padding: ['2rem', '0', '2rem', '0']

  # ===========================================================================
  # RANGÉE 2 : LE DASHBOARD (News, Thèses, Projets)
  # ===========================================================================
  - block: markdown
    content:
      title: 'Actualités & Activités'
      subtitle: ''
      text: |
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-6">
          
          <!-- Sous-colonne 1 : News (via un shortcode ou lien) -->
          <div class="bg-gray-50 dark:bg-zinc-900 p-6 rounded-xl border border-gray-100 dark:border-zinc-800">
            <h3 class="text-lg font-bold uppercase tracking-wider text-gray-800 dark:text-white border-b pb-2 mb-4">📢 News à venir</h3>
            <!-- Tu pourras insérer ici un shortcode de liste ou un résumé manuel -->
            <p class="text-sm text-gray-500 italic">Aucune actualité à venir pour le moment.</p>
          </div>

          <!-- Sous-colonne 2 : Thèses en cours -->
          <div class="bg-gray-50 dark:bg-zinc-900 p-6 rounded-xl border border-gray-100 dark:border-zinc-800">
            <h3 class="text-lg font-bold uppercase tracking-wider text-gray-800 dark:text-white border-b pb-2 mb-4">🎓 Thèses en cours</h3>
            <ul class="space-y-3 text-sm text-gray-600 dark:text-gray-300">
              <li><a href="/thesis/sujet-1" class="hover:text-blue-600 font-medium">Modélisation PLM et jumeau numérique...</a></li>
              <li><a href="/thesis/sujet-2" class="hover:text-blue-600 font-medium">Optimisation des supply chains résilientes...</a></li>
            </ul>
            <a href="/thesis/" class="block text-right text-xs text-blue-500 mt-4 hover:underline">Voir toutes les thèses &rarr;</a>
          </div>

          <!-- Sous-colonne 3 : Projets en cours -->
          <div class="bg-gray-50 dark:bg-zinc-900 p-6 rounded-xl border border-gray-100 dark:border-zinc-800">
            <h3 class="text-lg font-bold uppercase tracking-wider text-gray-800 dark:text-white border-b pb-2 mb-4">🚀 Projets en cours</h3>
            <ul class="space-y-3 text-sm text-gray-600 dark:text-gray-300">
              <li><span class="bg-blue-100 text-blue-800 text-xs px-2 py-0.5 rounded mr-1 font-semibold">ANR</span> <a href="/project/anr-test" class="hover:text-blue-600 font-medium">Projet Cyber-Physique DISP</a></li>
              <li><span class="bg-green-100 text-green-800 text-xs px-2 py-0.5 rounded mr-1 font-semibold">H2020</span> <a href="/project/europe-test" class="hover:text-blue-600 font-medium">Projet Européen Supply-Agility</a></li>
            </ul>
            <a href="/project/" class="block text-right text-xs text-blue-500 mt-4 hover:underline">Voir tous les projets &rarr;</a>
          </div>

        </div>
---