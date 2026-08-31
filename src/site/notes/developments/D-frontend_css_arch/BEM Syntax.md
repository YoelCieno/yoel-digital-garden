---
{"dg-publish":true,"permalink":"/developments/d-frontend-css-arch/bem-syntax/","tags":["css","frontend"],"noteIcon":"","dg-note-properties":{"tags":["css","frontend"]}}
---

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