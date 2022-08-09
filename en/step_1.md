<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
A <span style="color: #0faeb0">hyperlink</span> is a clickable link to another webpage. Links are usually underlined or otherwise styled to separate them from the rest of the text. 
</p>

In HTML the `<a>` tag is used to create links. 

+ You put the link text that appears on the webpage inside `<a>` and `</a>` 
+ The `href` attribute provides the web address (usually beginning with 'https:') of the page you want to link to 
+ You can also add `target="_blank"` to make the linked webpage open in a new tab in the web browser instead of replacing the current webpage  

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<p><a href="https://rpf.io/emoji" target="_blank">More emoji!</a></p>

--- /code ---

The appearance of the link is set by a rule for `<a>` elements in your style file. 

<iframe src="https://trinket.io/embed/html/c575a91355?toggleCode=true" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
