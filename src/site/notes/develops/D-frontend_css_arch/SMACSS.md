---
{"dg-publish":true,"permalink":"/develops/d-frontend-css-arch/smacss/","tags":["css","frontend","gardenEntry","gardenEntry","gardenEntry","gardenEntry","gardenEntry"],"noteIcon":""}
---

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
