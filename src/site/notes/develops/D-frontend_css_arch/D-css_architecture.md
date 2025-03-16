---
{"dg-publish":true,"permalink":"/develops/d-frontend-css-arch/d-css-architecture/","tags":["css","frontend","trends","gardenEntry","gardenEntry","gardenEntry","gardenEntry","gardenEntry"],"noteIcon":""}
---

## Introduction

- I have chosen this topic because usually is a sticking point. There are a lot of frontend developers who they know the minimum viable styles to code their features and create interface components that are easier to understand, maintain and reuse.

- Therefore we need the styles are accesibles, readable and simple. To do this we count with modular strategies or methodologies developed from a long time.
	- **OOCSS**: https://www.stubbornella.org/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/
		- Typos: https://github.com/stubbornella/oocss/wiki
		- https://github.com/stubbornella/oocss/  (main repo)
	-  **SMACSS**: http://smacss.com
	- **BEM**: https://nicolasgallagher.com/about-html-semantics-front-end-architecture/

### Maintainable CSS
We have switched to indicate that these are Layout rules, since we are impacting how the individual modules (the list items) are to be contained. The classes can be applied to the sub-navigation. The goal is create the result that we desire
### Less css styles

- [[develops/D-frontend_css_arch/OOCSS\|OOCSS]]
- [[develops/D-frontend_css_arch/SMACSS\|SMACSS]]
- [[develops/D-frontend_css_arch/BEM Syntax\|BEM Syntax]]
## Semantic vs non-semantic

```HTML
<!-- non semantic -->
<div class="red pull-left pb3">
<div class="grid row">
<div class="col-xs-4">
```

Non-semantic classes don't convey _what_ an element represents. At most they give you an idea of what an element _looks_ like. Atomic, visual, behavioural and utility classes are all forms of non-semantic classes.
Semantic classes don't convey their styles, but that's fine—that's what CSS is for. Semantic classes mean something to HTML, CSS, Javascript and automated functional tests.
Let's look at why semantic classes usually work best.
### Some other ideas

https://heydonworks.com

![Captura de pantalla 2023-10-02 a las 21.34.28.png](/img/user/sources/img/Captura%20de%20pantalla%202023-10-02%20a%20las%2021.34.28.png)