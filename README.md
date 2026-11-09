# Mes tâches — prototype iPhone

## Fonctionnalités
- Ajout rapide de tâches
- Dictée via le microphone du clavier iOS (dans Safari)
- Extraction simple des dates explicites : aujourd'hui, demain, jj/mm/aaaa, « le 30 avril »
- Catégories, projets, échéances, priorités, remarques et sous-tâches
- Filtres : toutes, aujourd'hui, à venir, en retard, terminées
- Export/import JSON pour sauvegarder et restaurer les tâches
- Interface responsive et mode PWA

## Important
Cette première version est un prototype local : les tâches restent dans le stockage du navigateur sur cet iPhone. Il n'y a PAS encore de sauvegarde cloud, de compte utilisateur, de chiffrement serveur ni de notifications push. Exporter régulièrement une sauvegarde JSON. La sauvegarde cloud sera ajoutée après choix et configuration d'un hébergement sécurisé.

La reconnaissance vocale se fait par la dictée native du clavier iOS : toucher le champ de saisie, puis le microphone du clavier. Le bouton « Dictée iPhone » place le curseur dans le champ.

## Installation
Le dossier doit être hébergé en HTTPS pour l'installation PWA. Sur iPhone : ouvrir l'URL dans Safari > bouton Partager > Sur l'écran d'accueil.
