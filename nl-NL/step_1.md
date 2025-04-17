Google Material Icons zijn een reeks aanpasbare vectorpictogrammen die zijn ontworpen en onderhouden door Google. Ze worden veel gebruikt bij de ontwikkeling van web- en mobiele apps om de visuele aantrekkelijkheid van gebruikersinterfaces te verbeteren.

Open [fonts.google.com](https://fonts.google.com/icons){:target="_blank"}. De link wordt geopend in een nieuw tabblad.

![De Google Fonts-pictogrammen pagina met verschillende pictogrammen en de zoekbalk die wordt weergegeven.](images/google-icons.png)

Je kunt op de website naar specifieke pictogrammen zoeken. De website biedt een uitgebreide bibliotheek met pictogrammen, elk met een unieke naam. Je kunt pictogrammen vinden die geschikt zijn voor jouw project door de zoekfunctie op de site te bekijken of te gebruiken.

Klik op het pictogram dat je wil toevoegen. Er wordt een extra venster geopend met instructies over hoe je het pictogram aan jouw project kunt toevoegen. ![De Google Fonts pictogrammen pagina met het home icoon geselecteerd. Er is een instructievenster geopend, waarin wordt getoond hoe je het pictogram aan een project toevoegt.](images/google-selectedicon.png)

### Materials Icon Font opnemen in HTML

Voeg het element `<link>` toe aan de sectie `<head>` van je HTML-bestand om het lettertype Material Icons op te nemen. Met deze link importeer je het Material Icons-lettertype uit de Google Fonts API.

--- code ---
---
language: html
filename: index.html
line_numbers: true
---

    <head>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <link rel="stylesheet" href="style.css">
      <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    </head>
  
--- /code ---

### Material Icons gebruiken in HTML

Vervolgens kun je Material Icons in je HTML gebruiken door de juiste klasse aan een HTML element toe te voegen.

Bijvoorbeeld:

--- code ---
---
language: html
filename: index.html
line_numbers: true
---

    <body>
      <div class="toggle-container">
        <span class="material-symbols-outlined">home</span>
      </div>
    </body>
  
--- /code ---

### CSS Styling

Je kunt de aangepaste stijl van het pictogram toepassen op het CSS-stijlblad van je project en het personaliseren naar je eigen voorkeur.

--- code ---
---
language: css
filename: style.css
line_numbers: true
---

.material-symbols-outlined {
      font-variation-settings:
      'FILL' 0,
      'wght' 400,
      'GRAD' 0,
      'opsz' 24
}
  
--- /code ---

### Testen

Voer je project uit om na te gaan of de Material Icons correct worden weergegeven. Als alles goed is ingesteld, zie je dat de pictogrammen zijn opgemaakt volgens de opgegeven klassen.