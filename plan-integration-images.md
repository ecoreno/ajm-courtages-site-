# Intégration des images — AJM Courtage

Chaque image est associée à la page où elle a le plus de sens (cohérence avec le texte déjà présent sur le site).

| Fichier (dans `/assets`) | Page / section | Pourquoi |
|---|---|---|
| `photo-sante-medecin-patient.jpg` | **Assurance Santé** — en tête de page, à droite du texte d'intro | Médecin + patient = illustre directement "consultations, hospitalisation, optique, dentaire" |
| `photo-auto-agent-cliente.jpg` | **Assurance Auto** — en tête de page | Conseiller avec tablette face à une automobiliste : incarne le rendez-vous conseil |
| `photo-moto-agent-motarde.png` | **Assurance Moto** — en tête de page | Conseiller + motarde équipée, avec la moto : cohérent avec "scooter, routière, sportive, équipements" |
| `photo-habitation-plan-cles.jpg` | **Assurance Habitation** — en tête de page | Plan de logement + clés sur la table basse : signal fort "logement / propriété" |
| `photo-emprunteur-bureau.jpg` | **Assurance Emprunteur** — en tête de page | Réunion en bureau avec tablette/graphiques + document : registre plus formel, adapté à un dossier de prêt |
| `photo-prevoyance-famille-multigen.jpg` | **Prévoyance** — en tête de page | Famille sur trois générations : illustre la protection dans la durée (arrêt de travail, invalidité, décès) |
| `photo-chien-chat-famille.jpg` | **Assurance Chien & Chat** — en tête de page | Même scène salon, mais centrée sur les animaux (chien + chat), sans le plan de logement |
| `photo-cabinet-poignee-de-main.jpg` | **Page d'accueil**, section *"Pourquoi AJM Courtage ?"* ou une page *"À propos"* si vous en créez une | Poignée de main + équipe : renforce "indépendance" et "accompagnement humain" |
| `photo-famille-salon.jpg` | **Page d'accueil**, section *"Obtenez une réponse adaptée à votre situation"* (juste au-dessus du formulaire de devis) | Rassure avant de remplir le formulaire |
| `illustration-marque-bouclier.jpg` | Utilisable comme **image de partage (Open Graph / réseaux sociaux)**, ou en fond discret derrière le bloc "Nos assurances" en page d'accueil | Illustration de marque (bouclier + mains + famille), cohérente avec le logo mais pas assez "photo réelle" pour une page produit |
| `icon-sante-prevoyance.png` | Icône de la carte **Assurance Santé** et **Prévoyance** dans "Nos assurances" (accueil) | Recadrée depuis votre planche d'icônes — cohérente avec le style déjà utilisé sur le site |
| `icon-habitation.png` | Icône de la carte **Assurance Habitation** | idem |
| `icon-auto-moto.png` | Icône des cartes **Assurance Auto** et **Assurance Moto** | idem |
| `icon-famille-emprunteur.png` | Icône de la carte **Assurance Emprunteur** | idem |

`photo-...(hero screenshot)` et la capture du site n'ont pas été réutilisées : ce sont des captures de référence, pas des visuels à publier.

## Remarque importante

Je n'ai pas d'accès direct au dépôt / à l'hébergement Netlify du site (`ajmcourtagesite.netlify.app`), donc je ne peux pas pousser ces changements moi-même sur le site en ligne. Ce dossier contient :

- `devis-form.html` — le formulaire de devis corrigé, autonome et fonctionnel (multi-besoins + priorité santé sur 4 étoiles), à transmettre à votre développeur pour l'intégrer à la place du formulaire actuel (section `#devis` / `#lead-form`).
- `assets/` — les images renommées et prêtes à l'emploi, avec les 4 icônes recadrées depuis votre planche d'origine.
- ce guide de placement.
