# Fusko

**Fusko** est un outil basé sur le web pour créer, organiser et prévisualiser des composants HTML, CSS et JavaScript.

**Fusko** is a web-based tool for creating, organizing, and previewing HTML, CSS, and JavaScript components.

## Fonctionnalités / Features

1. **Ajout et Édition de Composants / Add and Edit Components** : Ajoutez des composants HTML, CSS et JS à partir de catégories regroupées. Éditez le contenu via l'éditeur intégré ACE.
2. **Explorateur de Stockage / Storage Explorer** : Visualisez et gérez `IndexedDB`, `localStorage`, et les cookies via une interface modale détaillée.
3. **Glisser-Déposer / Drag-and-Drop** : Organisez facilement les composants en les déplaçant dans l'interface de création.
4. **Aperçu en Direct et Téléchargement / Live Preview and Download** : Prévisualisation en temps réel du HTML généré avec une option de téléchargement sous `index.html`.
5. **Réinitialisation et Bascule des Catégories / Reset and Toggle Categories** : Réinitialisez tous les composants ou basculez la visibilité des catégories pour une navigation simplifiée.

## Étendre Fusko / Extending Fusko

1. **Ajouter un Bouton / Add a Button** : Insérez `<button class="btn-html" onclick="addBlock('MY COMPONENT')">MY COMPONENT</button>` dans la catégorie souhaitée.
2. **Définir le Contenu par Défaut / Define Default Content** : Mettez à jour `getDefaultContent` pour configurer les valeurs par défaut de votre composant.
3. **Mise à Jour de la Génération HTML / Update HTML Generation** : Assurez-vous que votre composant est bien positionné dans `generateHTML`.

---

## Détails Techniques / Technical Details

- **ACE Editor** pour l'édition en ligne avec surlignage de la syntaxe / for in-line editing with syntax highlighting.
- **LocalStorage** pour sauvegarder l'état des composants / to save component state.
- **Glisser-Déposer / Drag-and-Drop** pour une organisation facile des composants.

---

Sous licence [GPL v3](https://www.gnu.org/licenses/gpl-3.0.html) / Licensed under [GPL v3](https://www.gnu.org/licenses/gpl-3.0.html).
