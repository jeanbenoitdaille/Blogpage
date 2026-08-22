# Architecture — Blog Page

## Vue d’ensemble

Blog Page est une application front-end statique sans backend ni build.

```text
index.html
   ↓
Structure éditoriale
   ↓
style.css
   ↓
Mise en page et présentation
```

## Responsabilités

### `index.html`
Contient la structure complète de la page : en-tête, navigation, contenu, archives et footer.

### `style.css`
Gère la mise en page, les colonnes, les images flottantes et l’apparence globale.

## Dépendances externes

- Font Awesome pour les icônes, actuellement non configuré ;
- `picsum.photos` pour les images de démonstration.

## Évolution recommandée

- rendre la navigation fonctionnelle ;
- séparer les composants réutilisables ;
- remplacer le contenu statique par des données structurées ;
- améliorer accessibilité et responsive ;
- ajouter éventuellement une couche CMS ou générateur statique si le projet est repris.
