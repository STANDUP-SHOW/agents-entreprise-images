# Compte rendu du 5 novembre 2026 : redacteur-quotidien-3 (rédacteur iAgent)

Rubrique `questions-pme-ia`. Connecteur « BLOG Agents-Entreprise.fr » présent, rubrique présente, Pixabay opérationnel (clé Unsplash absente, non nécessaire). **5 articles publiés.**

## Publiés

| # | Question | Thème | Lien | Mots | Solutions comparées | Photo |
|---|---|---|---|---|---|---|
| 1 | Quel matériel faut-il pour faire tourner une IA en local dans une PME ? | cloud-hybride-local | https://agents-entreprise.fr/article/materiel-ia-locale-pme-serveur-station-quel-budget | ≈ 2 800 | NVIDIA DGX Spark, Ollama, LM Studio, Mistral AI Enterprise, OVHcloud AI Endpoints, iAgent | Pixabay 5737958, JESHOOTS-com |
| 2 | Faut-il une analyse d'impact (AIPD) avant de déployer un agent IA dans une PME ? | donnees-securite-conformite | https://agents-entreprise.fr/article/aipd-analyse-impact-avant-deployer-agent-ia-pme | ≈ 2 740 | Claude Team, OneTrust, Dust, Dastra, outil PIA de la CNIL, iAgent | Pixabay 3196481, AymaneJed |
| 3 | Faut-il former ses salariés à l'IA, et comment financer ces formations dans une PME ? | organisation-humain | https://agents-entreprise.fr/article/former-salaries-ia-pme-financement-obligations | ≈ 2 480 | Google AI Essentials, Claude Academy, Pix / Pix Pro, DataScientest, iAgent | Pixabay 4784909, 14995841 |
| 4 | Un agent IA peut-il relancer les factures impayées des clients d'une PME ? | metiers-process | https://agents-entreprise.fr/article/agent-ia-relancer-factures-impayees-clients-pme | ≈ 2 320 | HighRadius, Tesorio, Upflow, Chaser, Sidetrade, iAgent | Pixabay 544180, Patrice_Audet |
| 5 | Quel assistant IA choisir pour une PME : ChatGPT, Claude, Gemini ou Mistral ? | choisir-une-solution | https://agents-entreprise.fr/article/quel-assistant-ia-choisir-pme-chatgpt-claude-gemini-mistral | ≈ 2 520 | ChatGPT Business, Claude Team, Gemini (Google Workspace), Mistral AI Team, Dust, iAgent | Pixabay 594091, StartupStockPhotos |

5 thèmes différents, dont 1 cloud / hybride / local et 1 question opérationnelle (relance des impayés). Couvertures : `articles/<slug>.webp`, 1280 × 720, WebP qualité 80, vérifiées en 200 `image/webp` avant chaque publication. Registre partagé mis à jour après chaque publication (52 entrées en fin de run). Typographie française appliquée (espaces fines insécables avant « : ; ! ? », espaces insécables dans les guillemets).

## Offre iAgent
- `registre/fiche-offre-iagent.md` relue et mise à jour une fois (pages /, /pricing, /local-ai, /box, /security, /workforce, /catalogue, /faq, /blog). **Aucun changement de prix ni de produit** par rapport au 04/11/2026. Ajouts : 423 activités et 13 680 tâches décrites. La Station iAgent reste « disponible en 2027 » et n'est présentée nulle part comme disponible.
- Page supplémentaire consultée le 05/11/2026 pour l'article 4, non encore reportée dans la fiche : https://iagent.agency/agents/agent-de-recouvrement (Agent de recouvrement : protocole par paliers, mise en demeure seulement sur décision du responsable, vérification de l'absence de contestation et de délai consenti, suivi des promesses de paiement, point du soir ; logiciels cités : Sage 100, Pennylane, Odoo, Evoliz, HubSpot CRM, Aircall, Microsoft 365 ; niveau d'agent non précisé). À intégrer à la fiche lors du prochain run.
- Aucun objectif chiffré de part locale trouvé : non cité.

## Questions écartées
- ChatGPT Business seul (prix) : page de tarifs rendue en JavaScript, montant non lisible depuis le conteneur ; l'offre est décrite dans l'article 5 avec la mention « montant non relevé ».
- Microsoft 365 Copilot : microsoft.com bloqué ; Copilot seulement mentionné dans l'article 5, sans conditions ni prix.
- Prix des forfaits Google Workspace : non affichés au rendu depuis le conteneur ; décrits sans montant.

## Réserve (candidates non utilisées)
1. « Comment choisir parmi les solutions d'IA souveraines référencées par l'État ? » (choisir une solution). Preuve : AMI France 2030, https://www.entreprises.gouv.fr/files/files/presse/2026/665_-_CP_-_France_2030_Lancement_dun_Appel_a_Manifestation_dInteret_AMI_pour_identifier_des_solutions_souveraines_dIA_pour_les_PME_et_ETI.pdf
2. « Un agent IA peut-il émettre les factures électroniques d'une PME en 2027 ? » (métiers, angle émission, à garder pour 2027). Preuve : FAQ DGFiP facturation électronique.
3. « L'IA n'est une priorité que pour 18 % des TPE-PME : par où commencer quand on n'a pas de projet ? » (organisation et humain). Preuve : baromètre France Num 2026, https://www.actuia.com/actualite/40-des-tpe-pme-utilisent-lia-mais-19-seulement-la-paient/
4. « Un agent IA peut-il analyser et classer les documents d'une PME (contrats, courriers) ? » (métiers et process ; 13 % des TPE-PME le font, +7 points). Preuve : https://www.entreprises.gouv.fr/espace-presse/barometre-france-num-2026-quatre-tpe-pme-sur-dix-utilisent-desormais-lintelligence

## Incidents
- Hôtes inaccessibles depuis le conteneur : openai.com, microsoft.com, banque-france.fr, alternativeto.net (403), legifrance (403) ; lejournaldesentreprises (connexion réinitialisée) ; page d'aide Mistral en 404. Contournements : source officielle mistral.ai/news pour Le Chat Enterprise ; sources non utilisées sinon.
- CDN Pixabay en 429 : nouvelles tentatives temporisées, sans erreur finale.
- Images : photo 740202 écartée (logo CASIO et autocollant Windows visibles) ; petite inscription « DELL » floutée sur la photo 544180 ; petite inscription sous l'écran floutée sur la photo 594091.
- Relecture : citations directes ramenées à 2 au maximum dans les articles 2 et 4 ; date non vérifiée d'un article Tissot remplacée par « consulté le 5 novembre 2026 ».
- Le nom « Le Chat » de Mistral est désormais présenté par l'éditeur sous le nom « Vibe » sur sa page de tarifs : l'article 5 le signale.
- Aucune erreur de l'outil `publish_article`, aucun retry nécessaire. Aucune clé d'API exposée.
