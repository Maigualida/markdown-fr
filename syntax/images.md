# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

<!--![texte alternatif]/ chemin/ a / img.jpg “titre optionnel”-->

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
<!--![texte alternatif][id]
[id] url/ a / image “titre optionnel”-->

Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

---

Here's a quiz about markdown images.
<!--Ici c’est un quiz sur les images markdown -->

Select the valid images:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`
<!--Sélectionner les images valides:
-[]`[Google logo]( https://www.google.ru/ logo.png)`)
- [x] `![](https://www.google.ru/logo.png)`-->

> Images must be prefixed with an exclamation mark.
The alternative text and a title are optional.
<!--Les images doivent être précédées d'un point d'exclamation. Le texte alternatif et u n titre sont optionnel-->

What is true about the following line: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] if the url is 404, "Funny cat" will be displayed
- [ ] exclamation mark can be omitted in this case
- [ ] if the url is 404, "Share this" will be displayed
- [x] on mouse over the image "Share this" will be displayed

<!--Ce qui est vrai sur la ligne suivante: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] si le url est 404, "Funny cat" sera affiché
- [ ] Point d'exclamation peut être omis dans ce cas
- [ ] si le url est 404, "Partager" s'affiche
- [x] Sur la souris sur l'image "Partager" sera affiché-->


> Similarly to links, images can have 3 parts: the alternative text, the url and a title. An exclamation mark is nesessary.

<!--De même pour les liens, les images peuvent avoir 3 parties: le texte alternatif, l'url et un titre. Un point d'exclamation est nécessaire.-->

---
