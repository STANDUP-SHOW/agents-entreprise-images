# Compte rendu du 4 novembre 2026 : redacteur-quotidien-2

Première exécution de la routine. Pixabay a répondu (200), le connecteur « BLOG Agents-Entreprise.fr » était présent et la rubrique `inspiration-americaine` existe. 12 articles publiés sur 12 prévus. Registre `registre/articles-publies.json` mis à jour après chaque publication (partagé avec les routines 1 et 3, qui ont publié en parallèle).

## Publiés

| # | Titre | Type | Rubrique | Lien | Mots (estimés) | Photo (Pixabay) |
|---|---|---|---|---|---|---|
| 1 | Base Power : la start-up texane des batteries domestiques en réseau | fiche | startups | https://agents-entreprise.fr/article/base-power-startup-americaine-batteries-domestiques | 879 (mesuré) | id 3088488, paulbr75 |
| 2 | Function Health : le bilan de santé par abonnement venu d'Austin | fiche | startups | https://agents-entreprise.fr/article/function-health-startup-americaine-bilans-sanguins | ≈ 900 | id 4944424, AhmadArdity |
| 3 | Hadrian : la start-up qui automatise l'usinage pour la défense | fiche | startups | https://agents-entreprise.fr/article/hadrian-startup-americaine-usines-automatisees | ≈ 900 | id 5770326, RobbieWi |
| 4 | Varda : la start-up qui veut fabriquer des médicaments en orbite | fiche | startups | https://agents-entreprise.fr/article/varda-startup-americaine-medicaments-espace | ≈ 950 | id 2141259, luvqs |
| 5 | Decagon : la start-up qui confie le service client à des agents IA | fiche | startups | https://agents-entreprise.fr/article/decagon-startup-americaine-service-client-ia | ≈ 900 | id 8754751, Telesolutionscallcentr |
| 6 | Rillet : le logiciel comptable à base d'agents IA qui défie NetSuite | fiche | startups | https://agents-entreprise.fr/article/rillet-startup-americaine-comptabilite-ia | ≈ 950 | id 7529921, Flyfin |
| 7 | Jump : l'IA qui prépare les rendez-vous des conseillers financiers | fiche | startups | https://agents-entreprise.fr/article/jump-startup-americaine-ia-conseillers-financiers | ≈ 950 | id 5382501, RonaldCandonga |
| 8 | Profound : la start-up qui mesure la visibilité des marques dans l'IA | fiche | startups | https://agents-entreprise.fr/article/profound-startup-americaine-visibilite-recherche-ia | ≈ 950 | id 620822, Firmbee |
| 9 | Tennr : l'IA new-yorkaise qui accélère l'orientation des patients | fiche | startups | https://agents-entreprise.fr/article/tennr-startup-americaine-orientation-patients | ≈ 950 | id 5710160, Maximilianovich |
| 10 | Modal : la start-up new-yorkaise qui loue le calcul IA à la seconde | fiche | startups | https://agents-entreprise.fr/article/modal-startup-americaine-cloud-ia | ≈ 950 | id 4922449, This_is_Engineering |
| 11 | Business model de Gamma : des présentations par IA rentables à 100 M$ | analyse | startups | https://agents-entreprise.fr/article/business-model-gamma-presentations-ia-rentable | ≈ 1 900 | id 4702060, This_is_Engineering |
| 12 | 5 startups américaines d'IA verticale qui automatisent le bureau | inspiration | inspiration-americaine | https://agents-entreprise.fr/article/inspiration-americaine-ia-verticale-metiers-bureau-2026-11-04 | ≈ 2 400 | id 4898536, Deeezy |

Équilibre des 10 fiches : 6 startups dont le produit principal est l'IA (Rillet, Decagon, Jump, Profound, Tennr, Modal) et 4 hors IA (Base Power, Function Health, Hadrian, Varda) ; secteurs énergie, santé, industrie, spatial, comptabilité, service client, gestion de patrimoine, marketing, cloud ; États : Californie 4, New York 3, Texas 2, Utah 1. Thème Inspiration : IA verticale appliquée aux métiers de bureau (Rillet, Decagon, Jump, Tennr, Profound, toutes fichées le jour même et liées).

## Startups écartées

- Supabase : siège contesté (DealStreetAsia la présente comme une start-up singapourienne).
- fal : déjà traitée aujourd'hui par la routine 1 (levée de 1,3 Md$).
- Mercor : écartée par prudence (contentieux rapporté avec Scale AI, non approfondi).
- ElevenLabs, Lovable : siège hors des États-Unis ou ambigu.
- Ramp, Glean, Clay : fondées avant 2020.

## Réserve pour les prochains jours

- Gamma (San Francisco, 2020) : 100 M$ d'ARR rentable, série B de 68 M$ à 2,1 Md$ (TechCrunch, 10/11/2025). Analysée aujourd'hui, pas encore fichée.
- OpenEvidence (Miami) : série D de 250 M$ à 12 Md$ menée par Thrive et DST (Business Wire, 21/01/2026). Année de création à vérifier.
- Ambience Healthcare : série C de 243 M$ co-menée par Oak HC/FT et a16z, partenariat exclusif avec la Cleveland Clinic (SiliconANGLE et Fierce Healthcare, 29/07/2025). Année de création à vérifier.
- Saronic (Austin) : série D de 1,75 Md$ à 9,25 Md$ menée par Kleiner Perkins (PR Newswire, 31/03/2026). Défense, à traiter avec prudence.
- Juicebox (San Francisco, YC S22) : série B de 80 M$ à 850 M$ menée par DST Global, plus de 5 000 clients revendiqués (Business Wire, 10/03/2026).

## Incidents et points à connaître

- Plusieurs pages ont répondu 403 (Business Wire, Fierce Healthcare, gamma.app/pricing, AI Magazine) : d'autres sources ont été utilisées. Les tarifs de Gamma proviennent du relevé publié par Dupple le 14/10/2026.
- Typographie : les espaces avant « : ; ? ! » sont des espaces normales, pas des espaces insécables (l'outil de publication ne permet pas de les insérer de façon fiable).
- Contrôle a posteriori, quatre formulations générales sans source précise sont restées dans les textes publiés (aucune ne porte sur un chiffre) : Varda (comparaison de la capsule à « une machine à laver »), Tennr (« un marché sans grand concurrent historique »), Jump (obligations réglementaires de traçabilité du conseil en France et aux États-Unis), Gamma (intégration de l'IA par Microsoft et Google dans leurs outils de présentation). La routine ne modifie jamais un article publié : à corriger à la main si souhaité.
- Quelques couvertures pèsent moins que la cible de 75 Ko (20 à 41 Ko) car les photos sont peu détaillées ; elles sont bien en 1 280 × 720, WebP qualité 80.
- Aucune erreur de publication, aucun retry nécessaire.
