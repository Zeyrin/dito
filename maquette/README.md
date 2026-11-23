# Maquette de refonte hellodito.com

Prototype statique (un seul fichier `index.html`) pour montrer à quoi pourrait ressembler la refonte. Ouvrir le fichier dans un navigateur. Trois vues : `#accueil`, `#grand-format`, `#devis`. Le formulaire de devis ne fait rien partir.

## Avant / après côté SEO

| | Site actuel | Maquette |
|---|---|---|
| Balise title | « Hello Dito » | « Imprimerie à Monaco \| Hello Dito, Fontvieille », une par page |
| Meta description | Identique au titre | Rédigée par page, avec les services et « Monaco » |
| Titre H1 | Aucun titre descriptif visible | « Votre imprimerie à Monaco », « Impression grand format à Monaco » |
| Pages services | Catalogues issuu / fliphtml5 peu lisibles par Google | Une page par service avec texte, tableau des supports, conseils |
| Données structurées | Aucune | LocalBusiness (adresse, téléphone), FAQ prévue |
| Langues | Bouton `?changeLang=en` | URL `/en/` avec hreflang |
| Conversion | Lien « Devis » vers une page contact | Formulaire de devis guidé, CTA sur chaque page |
| URL | `index.php?page=6` | `/grand-format/` (prévu pour le vrai site) |

## Reste à faire pour la vraie version

- Vraies photos de l'atelier et des produits, logo officiel.
- Horaires, page Mentions légales.
- Contenus des autres pages services et version anglaise.
- Redirections 301 des anciennes URL `index.php?page=N`.
