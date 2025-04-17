Les icônes Google Material sont un ensemble d'icônes vectorielles personnalisables conçues et mises à jour par Google. Elles sont largement utilisées dans le développement d'applications web et mobiles pour améliorer l'attrait visuel des interfaces utilisateur.

Ouvre [fonts.google.com](https://fonts.google.com/icons){:target="_blank"}. Le lien s'ouvrira dans un nouvel onglet.

![La page des icônes de Google Fonts avec diverses icônes et la barre de recherche affichée.](images/google-icons.png)

Tu peux rechercher des icônes spécifiques sur le site web. Le site web fournit une vaste bibliothèque d'icônes, chacune avec un nom unique. You can find icons suitable for your project by browsing or using the search functionality on the site.

Clique sur l'icône que tu souhaites ajouter. This will open some instructions on how to add the icon to your project. ![La page d'icônes Google Fonts avec l'icône d'accueil sélectionnée. Il y a un panneau d'instructions ouvert, montrant comment ajouter l'icône à un projet.](images/google-selectedicon.png)

### Inclure la police des icônes Material en HTML

Ajoute l'élément `<link>` dans la section `<head>` de ton fichier HTML pour inclure la police des icônes Material. Ce lien importera la police des icônes Material depuis l'API Google Fonts.

## --- code ---

language: html
filename: index.html
line_numbers: true
-------------------------------------------------------

```
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
</head>
```

\--- /code ---

### Utiliser les icônes Material en HTML

Tu peux ensuite utiliser les icônes Material dans ton HTML en ajoutant la classe appropriée à un élément HTML.

Par exemple :

## --- code ---

language: html
filename: index.html
line_numbers: true
-------------------------------------------------------

```
<body>
  <div class="toggle-container">
    <span class="material-symbols-outlined">home</span>
  </div>
</body>
```

\--- /code ---

### CSS styling

Tu peux appliquer les styles personnalisés de l’icône à la feuille de style CSS de ton projet et la personnaliser selon tes préférences.

## --- code ---

language: css
filename: style.css
line_numbers: true
-------------------------------------------------------

.material-symbols-outlined {
font-variation-settings:
'FILL' 0,
'wght' 400,
'GRAD' 0,
'opsz' 24
}

\--- /code ---

### Test

Exécute ton projet pour vérifier que les icônes Material sont affichées correctement. Si tout est correctement configuré, tu devrais voir les icônes stylisées en fonction des classes fournies.
