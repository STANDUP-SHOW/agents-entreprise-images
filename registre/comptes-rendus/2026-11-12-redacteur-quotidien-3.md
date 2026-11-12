# Compte rendu du 12 novembre 2026 : redacteur-quotidien-3 (rubrique questions-pme-ia)

Le site ZeyDo est de nouveau en ligne (il était hors service le 11/11 avec une erreur 402). Rien n'a bloqué le travail : le connecteur « BLOG Agents-Entreprise.fr » répond, la rubrique `questions-pme-ia` existe, Pixabay répond, et le dépôt d'images comme le registre sont à jour. **5 articles publiés.**

## Publiés

| # | Question | Thème | Lien | Mots | Solutions comparées | Photo |
|---|---|---|---|---|---|---|
| 1 | Un agent IA peut-il répondre aux appels d'offres publics à la place d'une PME ? | Métiers et process (marchés publics) | https://agents-entreprise.fr/article/agent-ia-repondre-appels-offres-publics-pme-memoire-technique | ≈ 2 740 | Responsive, AutogenAI, Claude Team, Explain, Tenderbolt, ZeyDo | Pixabay 6339361, sarahblocks |
| 2 | Un agent IA peut-il saisir les commandes de mes clients professionnels dans l'ERP ? | Métiers et process (ADV, commandes B2B) | https://agents-entreprise.fr/article/agent-ia-saisir-commandes-clients-b2b-grossiste-pme | ≈ 2 540 | Business Central Sales Order Agent, Nanonets, Esker, Mindee, ZeyDo | Pixabay 408222, delphinmedia |
| 3 | Avocat ou expert-comptable : peut-on confier des dossiers clients à un agent IA ? | Données, sécurité et conformité (secret professionnel) | https://agents-entreprise.fr/article/secret-professionnel-avocat-expert-comptable-agent-ia-donnees-clients | ≈ 2 550 | Harvey, Claude Team, Jimini, Mistral AI, ZeyDo | Pixabay 7236482, DrMonteiro |
| 4 | IA locale ou cloud : laquelle consomme le plus d'électricité pour une PME ? | Cloud, hybride ou local | https://agents-entreprise.fr/article/ia-locale-ou-cloud-consommation-electrique-pme | ≈ 2 630 | NVIDIA DGX Spark, Ollama, Mistral AI, OVHcloud AI Endpoints, ZeyDo | Pixabay 167969, AlexanderStein |
| 5 | Quelles décisions laisser à un agent IA, et lesquelles faire valider par un humain ? | Organisation et humain | https://agents-entreprise.fr/article/quelles-decisions-laisser-agent-ia-validation-humaine-pme | ≈ 2 640 | Zapier Agents, Business Central Sales Order Agent, Dust, n8n, ZeyDo | Pixabay 7882178, shareef3 |

Les mots sont comptés sur le Markdown, tableaux compris. Chaque couverture est enregistrée sous `articles/<slug>.webp` (1280 × 720, WebP qualité 80, pastille ZeyDo en bas à droite). Chaque URL a renvoyé 200 `image/webp` avant la publication. Toutes les photos ont été vérifiées : non générées par IA (`isAiGenerated` faux), sans logo ni marque, et jamais utilisées auparavant. Le registre a reçu 5 entrées et en compte 231 au total. Les 5 articles couvrent 4 thèmes différents, dont 1 question cloud / hybride / local (article 4) et 2 questions très opérationnelles (articles 1 et 2).

Preuves que les questions sont réellement posées : marche-public.fr (IA et marchés publics), Capterra (OrderScan), barreau de Paris (charte IA des cabinets), Siècle Digital (alerte de l'Arcep sur l'impact écologique de l'IA générative, 26/05/2026), et le blog de Zapier accompagné de la prévision de Gartner (40 % des projets d'IA agentique abandonnés d'ici 2027).

## Offre ZeyDo : changements constatés

- Le site est de nouveau accessible et les prix n'ont pas changé : collaborateur IA de 149 à 399 € HT par mois plus la consommation, Zed Commander de 249 à 349 € HT par mois, inclus à partir de 5 agents.
- La page d'accueil met en avant Victor, présenté comme « Zed Commander » et « bras droit ». Chaque équipe a désormais un « Team Commander ». La page ajoute aussi la phrase « Ce qui engage l'entreprise attend votre accord. »
- Le blog ZeyDo compte 25 articles (dernière mise à jour le 11/11). Le plus récent porte sur les biais et la discrimination des agents IA.
- Fiches d'agents ajoutées à la fiche offre : Assistant appels d'offres (AG-0513, André), Opérateur de saisie (AG-0005, Noah), ADV export (AG-1468, Amber).
- **Écart à la consigne :** la fiche offre a reçu **deux** commits au lieu d'un seul. Le premier est « Fiche offre ZeyDo : 2026-11-12 ». Le second, qui ajoute les fiches d'agents, a été regroupé avec la couverture de l'article 1. Le contenu est correct, mais à l'avenir il faudra réunir toutes les fiches d'agents avant le commit unique.

## Questions écartées

- « Un agent IA peut-il émettre les factures électroniques ? » : trop proche de l'article du 04/11 (règle des 90 jours).
- « Que change l'article 50 de l'AI Act (marquage des contenus) ? » : déjà traité le 08/11.
- « Le Diag Data IA de Bpifrance est-il utile ? » : recoupe l'article sur les aides publiques, et bpifrance.fr répond 403.
- « Faut-il une charte d'usage ou un référent IA ? » : trop proche des articles sur le shadow IA et sur le recrutement d'un spécialiste IA.
- « IA et données RH des salariés » : trop proche de l'article HDS du 11/11.

## Réserve (pour les prochains jours)

1. « Mistral Vibe convient-il à une PME ? » (à reprendre sous un angle différent de l'article du 05/11).
2. « Faut-il utiliser l'agent IA de Meta sur WhatsApp ? »
3. « IA et données RH (arrêts maladie, paie) : quelles précautions ? »
4. « Faut-il un référent IA ou une charte d'usage dans une PME ? »
5. « Un agent IA peut-il émettre les factures électroniques d'une PME ? » (à reprendre après le délai de 90 jours).
6. « Un agent IA peut-il discriminer des clients ou des candidats ? » (nouvel article du blog ZeyDo sur les biais).
7. « Combien coûte vraiment un projet d'IA agentique, et pourquoi 40 % seront abandonnés ? » (prévision de Gartner).

## Incidents

- Sites bloqués ou illisibles : rossum.ai et lefebvre-dalloz.fr (protection Cloudflare), guide PDF du CNB (404), lexisveille et bee4win (pages vides), legifrance (illisible avec curl, lisible avec WebFetch). Les affirmations qui reposaient sur ces sources ont été retirées.
- Photo écartée : Pixabay 8499901 montrait un logo « VITAL » sur le gilet et le casque. Elle a été remplacée par 167969 (article 4).
- Loopio et Conexiom ne sont pas présentés comme des offres américaines, car leur siège est au Canada.
- Prix des formules Zapier illisibles et devise des prix Mindee chargée par JavaScript : les articles indiquent « Non lisible » ou décrivent l'offre en crédits.
