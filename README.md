# Blog Page

Prototype de blog statique réalisé en HTML et CSS.

## Statut

- **Type :** projet historique / maquette front-end
- **Technologies :** HTML5, CSS3
- **État :** démonstrateur visuel

## Objectif

Ce projet explore la construction d’une page de blog complète avec en-tête, navigation, contenu principal, images flottantes, archives latérales, pied de page et liens sociaux.

## Fonctionnalités présentes

- en-tête avec identité visuelle ;
- navigation Blog / CV / Contact / Social ;
- contenu éditorial avec images flottantes ;
- colonne d’archives ;
- sitemap dans le footer ;
- icônes sociales ;
- bouton visuel de retour en haut.

## Structure

```text
Blogpage/
├── index.html
├── style.css
├── docs/
│   ├── ARCHITECTURE.md
│   └── ROADMAP.md
└── README.md
```

## Utilisation

Aucune installation n’est nécessaire.

```bash
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Dépendances externes

Le HTML prévoit Font Awesome, mais l’URL du kit est actuellement un placeholder. Les illustrations utilisent également `picsum.photos`.

## Limites actuelles

- contenu de démonstration ;
- navigation non fonctionnelle ;
- absence de JavaScript ;
- aucune gestion d’articles dynamiques ;
- aucune persistance ;
- dépendances externes non figées ;
- accessibilité et responsive à renforcer.

## Documentation

- [Architecture](docs/ARCHITECTURE.md)
- [Roadmap](docs/ROADMAP.md)
