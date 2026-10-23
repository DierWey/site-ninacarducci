# Nina Carducci — Site optimisé (SEO, performance, accessibilité)

Site vitrine de Nina Carducci, photographe portraits & événementiel à Bordeaux, repris et optimisé dans le cadre d'une mission freelance : rendre le site rapide, accessible et bien référencé.

**📊 Résultats mesurés (audits Lighthouse & WAVE, avant → après) :**

| Axe | Avant | Après |
|---|---|---|
| Performance | 57 % | **98 %** |
| SEO | 73 % | **100 %** |
| Accessibilité | 67 % | **100 %** |
| Erreurs WAVE | multiples | **0** |

Le détail de chaque action et de son impact figure dans le **[rapport d'optimisation](./docs/rapport-optimisation.pdf)**.

## Contexte

Le site d'origine existait mais était long à charger et ne générait aucun client. La mission, cadrée avec la cliente, couvrait cinq chantiers :

- optimiser les performances et le référencement global du site ;
- mettre en place le référencement local avec Schema.org ;
- ajouter les métas pour les réseaux sociaux ;
- corriger l'accessibilité ;
- livrer un rapport d'optimisation mesurant l'impact de chaque action.

## Optimisations apportées

### Performance

- Images redimensionnées aux dimensions d'affichage et converties en WebP — le poids passe de **30,08 MB à 1,20 MB**.
- Versions minifiées de Bootstrap (CSS et JS) réellement chargées par le HTML.

### SEO

- Ajout de la balise `<title>` et de la meta `description`.
- Correction de la hiérarchie des titres (`hn`) : un seul `h1`, puis `h2`/`h3`/`h4` en cascade cohérente.
- Ajout d'attributs `alt` sur les 12 images, avec des termes liés aux mots-clés du site (photographie, événements, émotions…).

### Accessibilité

- Remplacement de `<div>` génériques par des balises sémantiques (`header`, `nav`, `main`, `section`, `aside`).
- Attribution des `for`/`id` sur les labels du formulaire de contact.
- Indication de la langue du site (`lang="fr"`).
- Correction des contrastes insuffisants signalés par WAVE (chevrons du carrousel, menu de tri du portfolio).

### Référencement local & réseaux sociaux

- Microdonnées Schema.org au format JSON-LD : adresse, horaires d'ouverture, lien Instagram — validées par l'outil Google Rich Snippet.
- Balises Open Graph (Facebook) et Twitter Cards pour des aperçus enrichis lors des partages.

## Technologies

- HTML / CSS / JavaScript
- Bootstrap (versions minifiées)
- Aucune dépendance ajoutée : le site reste statique et léger

## Démarrage

Le site est entièrement statique — il suffit d'ouvrir `index.html` dans un navigateur.

```bash
git clone https://github.com/DierWey/site-ninacarducci.git
cd site-ninacarducci
open index.html   # ou double-clic sur le fichier
```

## Liens

- 🌐 Site en ligne : [dierwey.github.io/site-ninacarducci](https://dierwey.github.io/site-ninacarducci/)
- 📊 Rapport d'optimisation : [docs/rapport-optimisation.pdf](./docs/rapport-optimisation.pdf)
- 📁 Repo d'origine : [ninacarducci.github.io](https://github.com/ninacarducci/ninacarducci.github.io)
