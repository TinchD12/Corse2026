# Corse 2026 — guide familial révisé

Guide statique bilingue français / espagnol : 35 lieux, carte, filtres et favoris.

## Mettre à jour le site existant

Décompresser l’archive, puis déposer **tout son contenu** à la racine du dépôt `tinchd12/Corse2026`, en remplaçant les fichiers existants. Conserver le dossier `assets` et ses sous-dossiers. Il ne suffit plus de remplacer uniquement `index.html`.

Les fichiers indispensables sont `index.html`, `app.js`, `places.js` et `assets/`. Aucune compilation n’est nécessaire. Conserver le réglage GitHub Pages existant. Après le déploiement, recharger la page pour récupérer les nouveaux fichiers.

Les favoris et la langue du site précédent sont conservés sur le même navigateur grâce aux mêmes clés de stockage local.

## Contenu

- `places.js` : les 35 fiches et les sources photographiques.
- `app.js` : traduction, filtres, favoris et carte.
- `assets/photos` : une photo par lieu, en deux tailles WebP ; aucune image distante nécessaire à l’affichage des fiches.
- `CONTROLES.md` : résultats et limites des vérifications.
- `LIENS.json` : contrôle HTTP daté des 66 liens principaux.
- `PHOTOS.md` : provenance des photos et crédits identifiés.

MapLibre GL JS 5.6.1 et sa licence sont inclus dans `assets/vendor`. La carte utilise le fond OpenFreeMap. Elle demande une connexion Internet ; son indisponibilité n’empêche plus de consulter les fiches. Les indications de temps de route restent approximatives et ne sont pas du trafic en temps réel.

## Trajets depuis les hébergements

Les 35 activités ont un séjour conseillé (Calvi ou Porto-Vecchio), un trajet depuis La Signoria ou les Lofts de Sainte-Lucie et une comparaison depuis l’autre hébergement. Les boutons Itinéraire utilisent cette origine. Calculs et limites : ROUTES.md ; réponse routière détaillée : ROUTES.json.

