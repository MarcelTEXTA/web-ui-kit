# Web UI Kit (fr)

Bienvenue dans le kit d'interface utilisateur pour TEXTA web ! Ce kit est conçu pour vous aider à créer des interfaces utilisateur utilisant GlassEffects avec facilité et cohérence.

## Composants Inclus

- **Boutons** : Style GlassEffects pour les boutons primaires et secondaires.
- **RadioButtons** : Composants RadioButton avec effets de verre cochable.
- **Checkboxes** : Composants Checkbox avec effets de verre checkable.
- **Champs de Texte** : Champs de saisie avec effets de verre pour éditer du texte.
- **Cartes** : Composants de carte avec effets de verre pour afficher le contenu dans un cadre.
- **Modales** : Fenêtres modales avec effets de verre pour les dialogues.
- **Barres de Navigation** : Barres de navigation avec effets de verre.
- **Alertes** : Composants d'alerte avec effets de verre.
- **Badges** : Composants de badge avec effets de verre.
- **Barres de Progression** : Composants de barre de progression avec effets de verre pour afficher la progression d'une tâche.
- **Tooltips** : Composants d'infobulle avec effets de verre lorsque l'utilisateur passe la souris dessus.
- **Menus Déroulants** : Composants de menu déroulant avec effets de verre.
- **Onglets** : Composants d'onglet avec effets de verre.
- **Onglets verticaux** : Composants d'onglet vertical avec effets de verre.
- **Barres de Recherche** : Composants de barre de recherche avec effets de verre.

## Installation

Pour utiliser ce kit d'interface utilisateur, vous pouvez cloner le dépôt ou télécharger les fichiers nécessaires. Assurez-vous d'inclure les styles CSS et les scripts JavaScript dans votre projet.

```bash
git clone https://github.com/yourusername/web-ui-kit.git
```

## Utilisation

Importez les composants nécessaires dans votre projet et utilisez-les comme indiqué dans la documentation fournie avec chaque composant.

```html
<link rel="stylesheet" href="path/to/glass-effects.css">
```

Voici la liste des classes CSS disponibles pour les composants GlassEffects :
- `.glass-button`
- `.glass-radio`
- `.glass-checkbox`
- `.glass-input`
- `.glass-card`
- `.glass-modal`
- `.glass-nav`
- `.glass-alert`
- `.glass-badge`
- `.glass-progress-bar`
- `.glass-tooltip`
- `.glass-dropdown`
- `.glass-tab`
- `.glass-vertical-tab`
- `.glass-tab-item` (pour `tab` et `vertical-tab`)
- `.glass-accordion`
- `.glass-search-bar`

Pour l'arrière-plan, vous pouvez choisir une image et la mettre dans le dosser `assets/images/` puis définir le style CSS suivant :

```css
body {
    background: url('assets/images/your-background-image.jpg') no-repeat center center fixed;
    background-size: cover;
}
```

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez ajouter de nouveaux composants ou améliorer les composants existants, veuillez soumettre une pull request avec vos modifications.