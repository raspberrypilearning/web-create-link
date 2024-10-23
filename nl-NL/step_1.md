<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Een <span style="color: #0faeb0">hyperlink</span> is een klikbare link naar een andere webpagina. Links zijn meestal onderstreept of op een andere manier opgemaakt om ze van de rest van de tekst te scheiden. 
</p>

In HTML wordt de tag `<a>` gebruikt om links te maken:

- Je plaatst de linktekst die op de webpagina verschijnt tussen `<a>` en `</a>`
- Het `href` attribuut biedt het webadres (begint meestal met 'https:') van de pagina waarnaar je wilt linken
- Je kunt ook `target="_blank"` toevoegen om de geinkte webpagina te openen in een nieuw tabblad in de webbrowser in plaats van de huidige webpagina te vervangen

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<p><a href="https://rpf.io/emoji" target="_blank">Meer emoji!</a></p>

--- /code ---

Het uiterlijk van de link is ingesteld door een regel voor `<a>` elementen in je stijlbestand.

<iframe src="https://editor.raspberrypi.org/nl-NL/embed/viewer/web-create-link" width="600" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
