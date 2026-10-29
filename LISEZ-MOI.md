# CHRONOGRAMME V3 PREMIUM — Le cabinet des archives

Application d'histoire pour les collégiens de la 6e à la 3e, 100 % statique (GitHub Pages).

## Ce qui change en V3

- Nouvelle interface « Archives du temps », adaptée aux téléphones, tablettes et ordinateurs.
- Illustration originale WebP pour chacune des 51 publications historiques (ambiance artistique, pas documents d'époque).
- Nouveau « Cabinet des archives » : 8 enquêtes documentaires complètes, deux par niveau.
- Pour chaque dossier : 3 indices à consulter, 3 étapes (observer, croiser, conclure), questions guidées, explications et synthèse ; 24 questions au total.
- Étoiles de méthode, progression des dossiers et nouveaux badges dans le carnet.
- Recherche textuelle dans les 51 publications.
- Nouveau logo PNG, visuels des époques, navigation optimisée.

## Ce qui est conservé

- Les 51 enquêtes historiques (anachronisme, vrai/faux, datation, critique de source).
- La frise interactive, 12 fiches de révision et les jeux Chronologie, Dates mystères et Brevet express.
- Les réglages (thème clair/sombre, lecture facilitée), les préférences et le système de points.
- Le système d'export/import des sauvegardes au format JSON.

## Mise à jour GitHub Pages

1. Dans le dépôt GitHub servant à publier Chronogramme, extraire ce ZIP sur l'ordinateur.
2. Remplacer **index.html** à la racine du dépôt.
3. Copier **tout le dossier assets** de ce ZIP à la racine du dépôt, en conservant ses sous-dossiers `illustrations` et `posts`.
4. Valider les fichiers modifiés sur GitHub (commit / push).
5. Rafraîchir la page de l'application. Si une ancienne version est en cache, faire Ctrl + F5 (ordinateur) ou rouvrir la page sur téléphone.

**Important : ne pas copier seulement `index.html`.** Les nouveaux visuels et la feuille de style se trouvent dans `assets/`.

## Test local

Décompresser le ZIP et ouvrir `index.html` dans un navigateur récent, à côté du dossier `assets/`.
Le site n'a pas de serveur applicatif, de compte utilisateur ni de collecte de données.
Les données sont mémorisées via `localStorage` dans le navigateur : il faut exporter une sauvegarde pour transférer les résultats à un autre appareil.

## Conservation de la progression

Le stockage conserve la même clé locale que les versions précédentes (`chronogramme:v1`).
La progression existante des 51 publications est conservée dans le même navigateur et à la même adresse de site.
Par précaution, utiliser « Mon carnet → Exporter » avant toute mise à jour majeure.
Les nouveaux dossiers commencent vides, les enquêtes anciennes ne sont pas réinitialisées.

## Note pédagogique

Les personnages du fil, les « documents » et les extraits du cabinet d'archives sont des **reconstitutions pédagogiques**. Ils servent à apprendre à observer, contextualiser et confronter les sources ; ils **ne se substituent pas à des documents historiques authentiques**. Les images illustrent l'ambiance des époques et ne sont pas présentées comme des photographies de vestiges.
Le mode Brevet express est un entraînement non officiel, pas un sujet du diplôme national du brevet.

## Structure des fichiers

- `index.html` : application et activités.
- `assets/v3.css` : nouvelle direction artistique.
- `assets/icon.png` : icône d'application.
- `assets/illustrations/` : illustrations raster de périodes et des huit dossiers.
- `assets/posts/` : 51 couvertures raster des publications.

V3 testée sur les formats 390, 900 et 1440 px : navigation, dossiers, progression, défis, carnet et réglages.
