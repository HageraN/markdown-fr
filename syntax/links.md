# Liens

Markdown prend en charge deux styles de liens: en ligne et de référence

Dans les deux styles, le texte du lien est délimité par des [crochets].

Pour créer un lien en ligne, utilisez un ensemble de parenthèses régulières immédiatement après le crochet carré du texte du lien. À l'intérieur des parenthèses, placez l'URL où vous voulez que le lien pointe, ainsi qu'un titre facultatif pour le lien, entouré de guillemets. Par exemple:
```markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)
```

Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:
```markdown
This is [an example][id] reference-style link.
```

Vous pouvez éventuellement utiliser un espace pour séparer les ensembles de crochets:
```markdown
This is [an example] [id] reference-style link.
```

Ensuite, n'importe où dans le document, vous définissez votre étiquette de lien comme ceci, sur une ligne par elle-même:
```markdown
[id]: http://example.com/  "Optional Title Here"
```

** GitHub ** et ** GitBook ** prend en charge l'autolinking d'URL. Ils vont autolink l'URL standard, donc si vous souhaitez lier à une URL (au lieu de définir le texte du lien), vous pouvez simplement entrer l'URL et il sera transformé en un lien vers cette URL.

---

Voici un quiz sur les liens de Markdown.

Sélectionnez les liens valides:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> Le texte du lien est délimité par [crochets].

Quelles sont les informations correctes de ce lien: ```[a link](http://google.fr "google")```
- [ ] Le lien est https://google.fr
- [x] Le titre du lien est "google"
- [ ] Il affichera le texte "google"
- [x] Il affichera le texte "a link"

> Les liens peuvent avoir 3 parties: le texte, l'url et un titre.

---

