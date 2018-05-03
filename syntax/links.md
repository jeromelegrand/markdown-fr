# Links

Le Markdown supporte deux styles de liens: en ligne et par référence.

Dans les deux styles, le lien texte est délémité par des [accolades].

Pour créer un lien en ligne, utilise utilise un jeux de parenthèses directement après l'accolade fermante du lien. Dans les parenthèses, met l'URL ou tu veux pointer, avec un titre optionnel pour le lien, entourré par des guillemets. Par exemple:
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

You can optionally use a space to separate the sets of brackets:
```markdown
This is [an example] [id] reference-style link.
```

Then, anywhere in the document, you define your link label like this, on a line by itself:
```markdown
[id]: http://example.com/  "Optional Title Here"
```

**GitHub** and **GitBook** supports URL autolinking. They will autolink standard URLs, so if you want to link to a URL (instead of setting link text), you can simply enter the URL and it will be turned into a link to that URL.


---

Here's a quiz about markdown links.

Select the valid links:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> The link text is delimited by [square brackets].

What are the correct informations from this link: ```[a link](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> Links can have 3 parts: the text, the url and a title.

---

