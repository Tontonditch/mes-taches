# To Do — application personnelle

## Fonctionnalités
- Ajout rapide par saisie ou dictée vocale directe lorsque le navigateur prend en charge la Web Speech API.
- La dictée remplit le champ de tâche ; l'utilisateur peut relire puis appuyer sur « Ajouter la tâche ».
- Repli possible sur la dictée du clavier iOS si la dictée directe n'est pas prise en charge.
- Extraction simple des dates : aujourd'hui, demain, jj/mm(/aaaa), « le 30 avril ».
- Catégories, projets, échéances, priorités, remarques et sous-tâches.
- Filtres et export/import JSON.

## Limites importantes
Cette version reste un prototype local. Les tâches sont enregistrées dans le stockage du navigateur sur cet appareil. Il n'y a pas de compte utilisateur, de synchronisation entre appareils, de sauvegarde cloud, de chiffrement serveur ni de notifications push. Exporter régulièrement une sauvegarde JSON.

La dictée directe dépend du support de reconnaissance vocale du navigateur et des autorisations du microphone. Si elle n'est pas disponible, utiliser le microphone du clavier iOS.

## Publication
Héberger le contenu de ce dossier à la racine du dépôt GitHub Pages, en HTTPS.
