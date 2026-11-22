# PlantEvo Viewer

Il y a plus de 470 millions d'années, les plantes ont quitté l'eau. Pour y arriver, elles ont dû résoudre quatre problèmes : ne pas se dessécher, tenir debout, se reproduire sans eau et protéger leurs graines.
Ce site web raconte **comment les plantes sont passées de l'eau à la terre** avec surtout des images et de courts textes.

## Le parcours

| Étape | Ce qu'elle apporte |
| --- | --- |
| Algues | La vie dans l'eau |
| Mousses | Cuticule et stomates : les premières à sortir de l'eau |
| Fougères | Vaisseaux et vraies racines |
| Conifères | Pollen et graine nue |
| Graminées | Fleur et fruit, pollinisation par le vent |
| Dicotylédones | Fleur et fruit, pollinisation par les insectes |

## La structuration

Le site se structure comme suit:
- Une page d'accueil qui présente le projet
- Un menu de 6 cartes cliquables vers chaque groupe de plantes
- Une page par groupe : **algues, mousses, fougères, conifères, graminées, dicotylédones**
- Sur chaque page : l'appareil végétatif, la reproduction, et une photo prise sur le terrain avec sa position GPS
- Un lien « Retour au menu » sur chaque page

## Comment je l'ai construit

1. **Je dessine d'abord.** Chaque page commence par une maquette sur Figma.
2. **Je structure.** J'écris le HTML : `header`, `nav`, `main`, `footer`.
3. **Je mets en forme.** J'écris le CSS : `flex`, `grid`, couleurs, images.
4. **Je teste.** Je vérifie la page sur plusieurs le navigateur.

Chaque page se termine par une observation de terrain : une photo et ses coordonnées GPS.

## Ce que mes erreurs m'ont appris

- Un `id` mal écrit (`acceuil` au lieu de `accueil`) et le lien ne mène nulle part.
- Un espace oublié dans le nom d'un fichier image et l'image disparaît.
- Une image garde sa taille d'origine tant que le CSS ne lui impose pas la sienne.
- Un nom de classe doit être écrit exactement pareil dans le HTML et dans le CSS.
- Ne pas comprendre ce qu'on doit faire ralenti.
- Ne pas ranger ces images dans un dossier appartenant au projet fait qu'on a pas le chemin d'accès.
- Ne pas écrire le `alt` dans la déclaration de l'image peut ne pas être bénéfique.
- Ne pas connaitre le processus CSS peut faire tourner en rond dans le travail et pousser à utiliser l'IA.

## Technologies

- HTML5 pour la structuration, 
- CSS3 pour les couleurs et la mise en page,
- Figma pour le design de départ. 

## L'auteur

**KOUTOUAN AKUI ANGE CYRIACK**.
Agronome et développeur web en formation, à la Digital Farming School.

GitHub : https://github.com/angecyriack44-sketch/plantevo.git .
