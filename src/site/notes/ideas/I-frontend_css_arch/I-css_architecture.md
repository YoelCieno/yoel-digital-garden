---
{"dg-publish":true,"permalink":"/ideas/i-frontend-css-arch/i-css-architecture/","tags":["css","frontend","english","trends","ideas","gardenEntry","gardenEntry","gardenEntry","gardenEntry","gardenEntry"],"noteIcon":""}
---

## Introduction

- I have chosen this topic because usually is a sticking point. There are a lot of frontend developers who they know the minimum viable styles to code their features and create interface components that are easier to understand, maintain and reuse.

- Therefore we need the styles are accesibles, readable and simple. To do this we count with modular strategies or methodologies developed from a long time.
	- **OOCSS**: https://www.stubbornella.org/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/
	-  **SMACSS**: http://smacss.com
	- **BEM**: https://nicolasgallagher.com/about-html-semantics-front-end-architecture/

### Maintainable CSS
We have switched to indicate that these are Layout rules, since we are impacting how the individual modules (the list items) are to be contained. The classes can be applied to the sub-navigation. The goal is create the result that we desire
### Less css styles

### OOCSS
Object Oriented CSS (OOCSS)—and everything that comes with this paradigm shift—is the conceptual foundation for better interface design and development. It states that interfaces are made of multiple components, which should be re-used as much as possible.

Similar to object-oriented programming, **OOCSS focuses on flexible and reusable components, each doing one thing well**. This alone encompasses basic programming principles such as [single responsibility principle](http://en.wikipedia.org/wiki/Single_responsibility_principle), [separation of concerns](http://en.wikipedia.org/wiki/Separation_of_concerns) and [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself).

It also checks one essential UX and Graphic Design box: **Consistency**. By re-using a similar button design throughout the interface, users get familiar with it, and the app feels more intuitive each new session. With OOCSS, we’re merely re-using code, making it faster and easier to create more things, without adding significant overhead to the codebase. DRY CSS, people!
### SMACSS
There are five types of categories:
1. Base
2. Layout
3. Module
4. State
5. Theme
### The 7-1 Pattern
https://sass-guidelin.es/#the-7-1-pattern

Back to architecture, shall we? I usually go with what I call the _7-1 pattern_: 7 folders, 1 file. Basically, you have all your partials stuffed into 7 different folders, and a single file at the root level (usually named `main.scss`) which imports them all to be compiled into a CSS stylesheet.

- `base/`
- `components/`
- `layout/`
- `pages/`
- `themes/`
- `abstracts/`
- `vendors/`

And of course:

- `main.scss`
#### And
![Captura de pantalla 2023-09-28 a las 23.23.56.png](/img/user/sources/img/Captura%20de%20pantalla%202023-09-28%20a%20las%2023.23.56.png)
https://github.com/5t3ph/html-sass-jumpstart/tree/main/src/sass

### My conclusion
The **[class selector](http://semantic-portal.net/concept:1646 "The class Selector")** selects elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the name of the class.

In the example below, all HTML elements with class="center" will be red and center-aligned:
![Captura de pantalla 2023-09-28 a las 23.28.23.png](/img/user/sources/img/Captura%20de%20pantalla%202023-09-28%20a%20las%2023.28.23.png)
## BEM Syntax

```css
.block__element--modifier
```

- [Block](https://en.bem.info/methodology/quick-start/#block)
- [Element](https://en.bem.info/methodology/quick-start/#element)
	- [Should I create a block or an element?](https://en.bem.info/methodology/quick-start/#should-i-create-a-block-or-an-element)
- [Modifier](https://en.bem.info/methodology/quick-start/#modifier)
	- [Mix](https://en.bem.info/methodology/quick-start/#mix)

-  [File structure](https://en.bem.info/methodology/quick-start/#file-structure)

https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/
If you are familiar with OOCSS then you will no doubt be familiar with [the media object](http://stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code). In BEM form, the media object would now read:

```css
.media {}
.media__img {}
.media__img--rev {}
.media__body {}
```

Some of my experiences about css we need to know how the browser is working with this semantic:
http://semantic-portal.net/css-tutorial-syntax
http://semantic-portal.net/css-tutorial-syntax/summary
## Semantic vs non-semantic

```
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