# Contrôles — 22 septembre 2026

## Résultat

- 33 fiches conservées, relues en français et en espagnol et regroupées par zone.
- 33 photographies intégrées au site, chacune en deux tailles WebP. 18 sélections remplacées, dont les six images qui ne chargeaient pas. Les images de fond et de fiches ne dépendent plus d’un hébergeur extérieur.
- 23 liens descriptifs remplacés par des pages consacrées aux lieux. Priorité aux offices de tourisme ; la fiche Asco utilise Wikipédia.
- 66 liens principaux contrôlés par requête GET avec suivi des redirections : 33 pages descriptives et 33 liens Google Maps, tous en HTTP 200 au contrôle. Les titres des pages descriptives ont aussi été examinés.
- Catégories uniformes : 🏖️ plage, 🏛️ culture et patrimoine, 🌿 nature. Même pictogramme dans les filtres, fiches, favoris et marqueurs.
- Noms, durées et interface traduits en espagnol. Les noms propres des points d’accès sont conservés pour les retrouver dans Google Maps.

## Fonctionnement vérifié dans Chromium

- Les 33 fiches s’affichent et leurs 33 photos chargent sans erreur.
- Pas de débordement horizontal à 390 px de largeur.
- Filtres, changement de langue et persistance après rechargement.
- Un favori masqué par le filtre actif redevient visible avant le défilement.
- Le changement d’un favori ne recrée plus toutes les photos de la page.
- Des préférences locales mal formées ne bloquent pas le guide.
- L’indisponibilité de la carte n’empêche pas l’affichage des fiches.
- Carte MapLibre réelle avec les 33 marqueurs.

## Corrections éditoriales

Les excursions lointaines restent des options et les journées trop chargées ne sont plus présentées comme un enchaînement évident. Les indications trop optimistes pour Vizzavona, Ajaccio et le Coscione ont été retirées au profit d’une invitation à calculer le trajet. La route vers une plage est distinguée du point où laisser la voiture ou commencer la marche. Les recommandations relatives aux rivières renvoient aux informations locales du jour.

## Limites

Un HTTP 200 prouve que la page répondait au contrôle ; ce n’est pas une garantie permanente. Pour Google Maps, il confirme l’ouverture du service, pas la reconnaissance sur le terrain d’un parking ni un temps de conduite précis. Les durées de trajet restent approximatives et ne constituent pas des estimations de trafic en temps réel. L’ouverture saisonnière des sites et les conditions de circulation ou de baignade doivent être consultées avant la sortie.

Les tests de navigation ont été réalisés à partir d’une copie locale du site. Les accès externes du navigateur de test passent par les accès réseau disponibles dans l’environnement. La validation après publication sur GitHub Pages reste à effectuer.
