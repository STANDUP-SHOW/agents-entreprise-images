# Compte rendu du 4 novembre 2026 : redacteur-quotidien-3 (rédacteur iAgent)

Rubrique `questions-pme-ia`. Connecteur « BLOG Agents-Entreprise.fr » présent, rubrique présente, Pixabay opérationnel. **5 articles publiés.**

## Publiés

| # | Question | Thème | Lien | Mots | Solutions comparées | Photo |
|---|---|---|---|---|---|---|
| 1 | Cloud Act : une PME expose-t-elle ses données en utilisant une IA américaine ? | cloud-hybride-local | https://agents-entreprise.fr/article/cloud-act-pme-donnees-ia-americaine | ≈ 2 690 | Microsoft 365 Copilot, Claude Team, Le Chat (Mistral AI), OVHcloud AI Endpoints, Dust, iAgent | Pixabay 8118380, cookieone |
| 2 | AI Act : quelles obligations pour une PME qui utilise des agents IA ? | donnees-securite-conformite | https://agents-entreprise.fr/article/ai-act-obligations-pme-agents-ia | ≈ 2 490 | Claude Enterprise, Gemini (Google Workspace), Le Chat (Mistral AI), Dust, iAgent | Pixabay 4703926, advogadoaguilar |
| 3 | Quelles aides publiques pour financer un projet d'agent IA dans une PME ? | couts-roi | https://agents-entreprise.fr/article/aides-publiques-financer-projet-agent-ia-pme | ≈ 2 320 | Microsoft 365 Copilot Business, Claude Team, Le Chat (Mistral AI), OVHcloud AI Endpoints, iAgent | Pixabay 1979261, 089photoshootings |
| 4 | Facture électronique : un agent IA peut-il traiter les factures fournisseurs d'une PME ? | metiers-process | https://agents-entreprise.fr/article/facture-electronique-agent-ia-factures-fournisseurs-pme | ≈ 2 230 | Tipalti, Rossum (groupe Coupa), Pennylane, Esker, iAgent | Pixabay 1205044, jackmac34 |
| 5 | Shadow IA : que faire quand vos salariés utilisent ChatGPT sans autorisation ? | organisation-humain | https://agents-entreprise.fr/article/shadow-ia-salaries-chatgpt-sans-autorisation-pme | ≈ 2 400 | Microsoft 365 Copilot Business, Gemini (Google Workspace), Le Chat (Mistral AI), Dust, iAgent | Pixabay 4941164, This_is_Engineering |

5 thèmes différents, dont 1 cloud / hybride / local et 1 question opérationnelle (factures fournisseurs). Couvertures : `articles/<slug>.webp`, 1280 × 720, vérifiées en 200 `image/webp`.

## Offre iAgent
- Première version de `registre/fiche-offre-iagent.md` (aucune version antérieure, donc pas de comparaison possible).
- Points notables relevés : tarifs pilotes HT (agents 149 / 249 / 399 €, Box 69 / 139 / 249 € sur 24 mois, Task Commander 249 à 349 €, packs Starter 218 €, Team ≈ 599 à 749 €, Department dès 999 €), Station iAgent 64 Go à 349,90 €/mois **annoncée pour 2027**, catalogue de 1 772 métiers et 3 117 logiciels, programme de 50 entreprises pilotes, architecture « Quantum-Ready » décrite sur /security.
- Aucun objectif chiffré de part locale (type « 80 % ») trouvé sur les pages consultées : non cité.

## Questions écartées
- Cloud ou local pour une PME (formulation générique) : déjà traité (`agent-ia-hybride-pourquoi-associer-intelligence-artificielle-locale-et-cloud`) ; angle Cloud Act retenu à la place.
- Combien coûte un agent IA : déjà traité (`combien-coute-reellement-un-agent-ia`) ; angle aides publiques retenu.
- Qui est responsable si l'agent se trompe : déjà traité.
- Agent IA et RGPD des données clients : déjà traité (`chatbot-rgpd-conformite-vie-privee`, `agent-ia-et-donnees-confidentielles-...`).
- ChatGPT Business ou Enterprise pour une PME : pages officielles d'OpenAI inaccessibles (403) depuis l'environnement, donc pas de prix ni de conditions sourcés.

## Réserve (candidates non utilisées)
1. « Copilot, Le Chat ou Gemini : quel assistant choisir pour une PME de 20 salariés ? » (thème choisir une solution). Preuve : comparatifs PME 2026, https://tech-insider.org/fr/copilot-vs-chatgpt-2026/ ; https://geotoolbox.ai/fr/blog/prix-copilot
2. « Quel matériel faut-il pour faire tourner une IA en local dans une PME ? » (cloud-hybride-local, angle matériel). Preuve : https://kyra.conversionsystem.com/blog/ai-data-sovereignty-self-hosted-2026
3. « Faut-il une analyse d'impact (AIPD) avant de déployer un agent IA ? » (conformité). Preuve : fiches pratiques IA de la CNIL, https://www.cnil.fr/fr/les-fiches-pratiques-ia ; FAQ CNIL RIA.
4. « Comment former ses salariés à l'IA, et avec quels financements (Impulsion IA 2027, OPCO) ? » (organisation et humain). Preuve : https://www.entreprises.gouv.fr/priorites-et-actions/transition-numerique/accompagner-les-entreprises-dans-leur-transition/le-plan
5. « Comment choisir parmi les solutions d'IA souveraines référencées par l'État ? » (choisir une solution). Preuve : AMI France 2030, https://www.entreprises.gouv.fr/files/files/presse/2026/665_-_CP_-_France_2030_Lancement_dun_Appel_a_Manifestation_dInteret_AMI_pour_identifier_des_solutions_souveraines_dIA_pour_les_PME_et_ETI.pdf
6. « Un agent IA peut-il émettre les factures électroniques d'une PME en 2027 ? » (métiers, angle émission, à garder pour 2027). Preuve : FAQ DGFiP facturation électronique.

## Incidents
- Pages officielles inaccessibles depuis le conteneur (403/503) : openai.com et chatgpt.com, microsoft.com (tarifs Copilot), bpifrance.fr, scaleway.com, economie.gouv.fr. Contournement : prix Copilot sourcé par Le Monde Informatique (20/11/2025), Prêt Boost IA par la fiche CCI les-aides.fr, offres OpenAI et Scaleway non comparées.
- Push concurrent avec les routines 1 et 2 sur `couvertures` : rejets puis réussite après `pull --rebase` (aucune écriture d'autrui écrasée). Une première tentative avait créé un `registre/articles-publies.json` vide en parallèle de celui de la routine 1 : annulée avant push.
- Images : 4 premières photos retenues écartées après contrôle visuel (logos HP, VAIO, 3Com, Leitz visibles) et remplacées.
- Les URL raw des couvertures ont répondu 404 quelques minutes après le push (cache), puis 200 `image/webp` avant chaque publication.
- Typographie : les articles ont été publiés avec des espaces ordinaires avant « : ; ? » (pas d'espaces insécables).
- Aucune erreur de l'outil `publish_article`, aucun retry nécessaire.
