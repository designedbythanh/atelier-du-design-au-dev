# Atelier « Du design au dev » — le kit

AI Discipline · Bayonne · novembre 2026

Tout ce qu'il faut pour les 3 cas pratiques. Le cas est fictif : **Cabinet Les Allées**, un cabinet paramédical de Bayonne (4 praticiens, une secrétaire à mi-temps). N'utilisez pas de données confidentielles.

## Le cas

> Un cabinet paramédical veut une prise de RDV en ligne : choix du praticien, du motif, des créneaux, réservation par le patient.

## Comment utiliser un skill

1. Ouvrez une nouvelle conversation dans Claude.
2. Collez le contenu du skill au début du message.
3. Joignez les fichiers d'entrée du cas (bouton « + » ou glisser-déposer).
4. Lancez.

## Le déroulé (15 min par cas, en binôme designer + dev/PM)

1. Lancez le v0 et notez ce qui ne colle pas au cabinet (4 min).
2. Écrivez le v1, puis relancez (5 min).
3. Partagez avec une autre paire (4 min).

À rendre : un skill v1 + une sortie avant / après.

Chaque cas part de ses propres entrées : pas besoin d'avoir fini le précédent.

| Cas | Skill v0 | Entrées à joindre |
|---|---|---|
| 1 · Cadrage | [`skills-v0/cas1-cadrage.md`](skills-v0/cas1-cadrage.md) | [`donnees/cabinet.md`](donnees/cabinet.md), [`donnees/avis-patients.md`](donnees/avis-patients.md), [`donnees/notes-secretariat.md`](donnees/notes-secretariat.md) |
| 2 · Idéation | [`skills-v0/cas2-ideation.md`](skills-v0/cas2-ideation.md) | [`entrees/cas2-cadrage.md`](entrees/cas2-cadrage.md), [`entrees/cas2-idee-de-depart.md`](entrees/cas2-idee-de-depart.md) |
| 3 · Handoff | [`skills-v0/cas3-handoff.md`](skills-v0/cas3-handoff.md) | [`entrees/cas3-concept-retenu.md`](entrees/cas3-concept-retenu.md), [`entrees/cas3-prototype.html`](entrees/cas3-prototype.html), [`entrees/cas2-cadrage.md`](entrees/cas2-cadrage.md) |

Le prototype du cas 3 : téléchargez `cas3-prototype.html` (bouton « Download raw file ») et ouvrez-le dans votre navigateur.

## Écrire votre v1

Partez du [template d'une page](template/skill-template.md).

| Ce qu'on y met | Ce qu'on enlève |
|---|---|
| Le contexte que l'IA ne peut pas deviner | « En tant que designer senior… » |
| Vos critères de qualité | Les étapes « comment réfléchir » |
| Les erreurs que vous avez déjà vécues | Les quantités arbitraires (« 10 idées ») |
| Le format utile pour la personne suivante | Les templates rigides |
| « N'invente rien : signale ce qui manque » | |

## Après l'atelier

Les v1 de Thanh pour les 3 cas et un guide pour installer un skill seront ajoutés ici.

## Licence

Contenu sous [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.fr). Toutes les données (cabinet, praticiens, patients, avis) sont inventées.
