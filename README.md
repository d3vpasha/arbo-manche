# ARBO'Manche – site vitrine

Site vitrine d'ARBO'Manche, l'entreprise d'arboriste grimpeur de Titouan Lemonnier à Bricquebec-en-Cotentin (Manche).
HTML, CSS et JS natifs : aucune étape de build, aucune dépendance.

Production : https://arbo-manche.vercel.app

## Arborescence

```
index.html                    page unique, sprite d'icônes inline, JSON-LD
assets/css/styles.css         styles, variables de couleur, mode sombre
assets/js/main.js             menu mobile, apparition au défilement, année, formulaire mailto
assets/img/logo.svg           logo horizontal couleur
assets/img/logo-mono-blanc.svg logo blanc (footer, en-tête en mode sombre)
assets/img/favicon.svg        monogramme carré
robots.txt                    autorise tout, pointe vers le sitemap
sitemap.xml                   une seule URL
```

## Lancer en local

```sh
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## TODO

- Assurance : préciser l'assurance réellement souscrite (bandeau de réassurance).
- Email : remplacer `lemonnier.titouan@gmail.com` par une adresse professionnelle (contact, formulaire, JSON-LD).
- Zone d'intervention : faire confirmer la liste des communes.

## Versions

| Version | Date | Direction visuelle |
|---|---|---|
| v1 | 2026-10-14 | Vert forêt et brun écorce, hero en deux colonnes avec citation, cartes de services |
