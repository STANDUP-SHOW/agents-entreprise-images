# Compte rendu du 6 novembre 2026 : redacteur-quotidien-3 (rédacteur iAgent)

Rubrique `questions-pme-ia`. Connecteur « BLOG Agents-Entreprise.fr » présent, rubrique présente, Pixabay opérationnel. **5 articles publiés.**

## Publiés

| # | Question | Thème | Lien | Mots (sources comprises) | Solutions comparées | Photo |
|---|---|---|---|---|---|---|
| 1 | Un agent IA peut-il trier le courrier et classer les documents d'une PME ? | metiers-process | https://agents-entreprise.fr/article/agent-ia-classer-documents-courrier-pme | ≈ 2 800 | Google Document AI, Nanonets, Mindee, DocuWare, iAgent | Pixabay 1219889, helpsg |
| 2 | Abonnement par utilisateur ou paiement à l'usage : comment payer l'IA dans une PME ? | couts-roi | https://agents-entreprise.fr/article/abonnement-ou-paiement-usage-ia-pme-quel-modele-prix | ≈ 2 850 | Claude (Anthropic), API Gemini, Mistral AI, Dust, iAgent | Pixabay 5395615, WebTechExperts |
| 3 | Que faire si le service d'IA de votre PME tombe en panne : faut-il un plan B local ? | cloud-hybride-local | https://agents-entreprise.fr/article/panne-service-ia-pme-plan-b-local-continuite | ≈ 2 725 | Ollama, LM Studio, Mistral AI, OVHcloud AI Endpoints, iAgent | Pixabay 2558705, StockSnap |
| 4 | Peut-on donner à un agent IA l'accès à la messagerie de l'entreprise sans risque ? | donnees-securite-conformite | https://agents-entreprise.fr/article/agent-ia-acces-messagerie-entreprise-risques-securite | ≈ 2 720 | Claude (connecteur Gmail), Lindy, Mistral (Le Chat / Vibe), Mailbutler, iAgent | Pixabay 849828, StartupStockPhotos |
| 5 | Par où commencer avec l'IA quand on dirige une TPE ou une PME sans projet précis ? | deploiement-integration | https://agents-entreprise.fr/article/par-ou-commencer-ia-tpe-pme-sans-projet-premier-cas-usage | ≈ 2 720 | Zapier, Claude, Dust, n8n, iAgent | Pixabay 2284501, mwitt1337 |

5 thèmes différents, dont 1 cloud / hybride / local. Chaque article compare au moins 2 offres américaines et 2 offres françaises ou européennes, avec iAgent en solution recommandée. Les preuves que chaque question est réellement posée sont dans les entrées du registre. Couvertures : `articles/<slug>.webp`, 1280 × 720, WebP qualité 80, vérifiées en 200 `image/webp` avant chaque publication. Registre partagé mis à jour après chaque publication (78 entrées en fin de run).

## Offre iAgent
- `registre/fiche-offre-iagent.md` mise à jour (commit « Fiche offre iAgent : 2026-11-06 »). **Aucun changement de prix ni de produit.**
- Ajouts : section « Fiches d'agents consultées » (Agent de recouvrement, reporté du 05/11 ; Agent de classement AG-0007 ; Agent de collecte documentaire AG-0090) ; notes sur les menus « Créer votre entreprise », « Business plan », « Opportunités », « iAgent inside iAgent » ; arguments « Coût à grande échelle » et « Continuité » de la page local-ai.
- La Station iAgent reste « disponible en 2027 » et n'est présentée nulle part comme disponible.

## Questions écartées
- Responsabilité en cas d'erreur d'un agent IA : déjà traitée sur le blog iAgent, risque de recopie.
- Solutions d'IA souveraines référencées par l'État (AMI) : liste des lauréats non publiée.
- Box AI : site box.com bloqué (403) depuis le conteneur.
- Notion AI (prix non affichés au rendu) et Swiftask (mentions légales illisibles) : offres non retenues faute d'informations vérifiables.

## Réserve (candidates non utilisées)
1. « Un agent IA peut-il émettre les factures électroniques d'une PME en 2027 ? » Preuve : FAQ DGFiP facturation électronique.
2. « Comment choisir parmi les 88 offreurs du catalogue DGE / Hub France IA ? » Preuve : bilan « Osez l'IA » du 3 septembre 2026.
3. « Le Diagnostic Data IA de Bpifrance vaut-il la peine pour une PME ? » Preuve : même bilan.
4. « Un agent IA peut-il répondre au téléphone d'une PME ? » (iAgent Voice / standard téléphonique).
5. « SLA des fournisseurs d'IA : que vérifier dans le contrat ? » (SLA Vertex AI, OVHcloud).
6. « IA gratuite ou payante : que deviennent les données de la PME ? » (conditions de l'API Gemini, offres gratuite et payante).

## Incidents
- Hôtes inaccessibles : box.com (403), m-files.com (403) ; offres remplacées. Ancienne URL du PDF de l'ANSSI renvoyant du HTML : bon document trouvé sur messervices.cyber.gouv.fr (recommandations R9, R26, R27).
- Images : photo 1839191 écartée (logo DELL) ; photo 5475187 écartée (photomontage) ; marque ADTRAN floutée sur la photo 2558705 ; autocollant de casque flouté sur la photo 2284501.
- Couvertures des articles 1 (≈ 57 Ko) et 2 (≈ 31 Ko) sous la cible de 75 à 150 Ko, en qualité 80 conforme : images peu détaillées, sans impact visible.
- Typographie : espaces fines insécables non appliquées dans les textes publiés (espaces normales), car elles ne passaient pas de façon fiable dans l'appel de publication.
- Relecture : une affirmation non vérifiée retirée (article 1) ; une citation traduite de l'ANSSI remplacée par une paraphrase (article 5) ; une formulation non sourcée sur Zapier corrigée (article 5) ; pays des éditeurs (Lindy, Zapier, n8n, LM Studio, Ollama) vérifiés dans leurs conditions ou mentions légales.
- Aucune erreur de l'outil `publish_article`, aucun retry nécessaire. Aucune clé d'API exposée.
