# Frise chronologique

Un éditeur visuel gratuit pour créer des frises chronologiques, organiser des événements et des périodes, puis partager le résultat. L’interface est en français et fonctionne dans un navigateur moderne, sur ordinateur ou mobile.

**[Ouvrir l’application](https://courscircuit.github.io/TimelineGenerator/)**.

## Premiers pas

1. Ouvrez l’application et définissez le titre ainsi que les limites chronologiques dans les paramètres.
2. Ajoutez des événements et des périodes à l’aide des panneaux de l’éditeur ; modifiez leur contenu et leur présentation selon vos besoins.
3. Utilisez **Enregistrer** pour télécharger votre travail en JSON et **Charger** pour le reprendre plus tard. Un brouillon est également conservé dans le stockage local du navigateur, sous réserve des réglages de celui-ci.
4. Exportez la frise en PNG, PDF ou HTML avec les boutons correspondants. Une connexion Internet est nécessaire pour charger les bibliothèques utilisées par les exports PNG et PDF.

L’assistant IA prépare un texte à copier dans un outil d’IA externe. Vous pouvez ensuite importer la réponse au format JSON ; vérifiez les dates, les sources et les droits des images proposées avant de les utiliser. L’application ne fournit pas elle-même le service d’IA.

## Utilisation locale

Téléchargez les fichiers du dépôt et ouvrez `index.html` dans un navigateur récent, ou servez le dossier avec un serveur web statique. Aucun outil de compilation n’est nécessaire. Certaines fonctionnalités dépendent de l’accès à Internet : polices Google Fonts, bibliothèques d’export et images distantes éventuellement ajoutées à la frise.

## Données et services externes

Le brouillon est enregistré dans le navigateur. Les polices proviennent de Google Fonts et les bibliothèques d’export de cdnjs ; les requêtes correspondantes sont adressées à ces services. Si vous utilisez des images externes, votre navigateur contacte aussi leurs hébergeurs. Les données copiées dans un service d’IA sont soumises aux conditions de ce service.

## Licence et composants tiers

Le code de l’application est proposé sous [licence MIT](LICENSE). Les bibliothèques externes html2canvas et jsPDF sont elles aussi sous licence MIT ; leurs mentions et licences sont conservées dans [licences-tierces](licences-tierces/). Les polices Google Fonts et les images ajoutées par l’utilisateur peuvent être soumises à leurs propres licences.
