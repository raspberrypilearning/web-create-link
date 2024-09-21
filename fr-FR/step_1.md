<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Un <span style="color: #0faeb0">lien hypertexte</span> est un lien cliquable vers une autre page web. Les liens sont généralement soulignés ou stylisés pour les séparer du reste du texte. 
</p>

En HTML, la balise `<a>` est utilisée pour créer des liens :

- Tu places le texte du lien qui apparaît sur la page web entre `<a>` et `</a>`
- L'attribut `href` fournit l'adresse web (commençant généralement par 'https:') de la page vers laquelle tu souhaites créer un lien
- Tu peux aussi ajouter `target="_blank"` pour que la page web liée s'ouvre dans un nouvel onglet du navigateur web au lieu de remplacer la page web actuelle

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

<p><a href="https://rpf.io/emoji" target="_blank">Plus d'emojis !</a></p>

\--- /code ---

L'apparence du lien est définie par une règle pour les éléments `<a>` dans ton fichier de style.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/web-create-link" width="600" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
