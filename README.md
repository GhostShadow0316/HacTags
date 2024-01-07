<!-- README.md -->

# HacTags
> a javascript library that adds more attributes to html

---
---

## Features
- [x] change text, fg/bg color when hovered
- [x] change text, fg/bg color when clicked
- [x] change font style
- [x] add text decoration from attribute
- [x] change cursor
- [x] abbreviation

---
---

## Get Started
> Paste this in \<head\>:

```html
<script defer src="https://cdn.jsdelivr.net/gh/GhostShadow0316/HacTags/hactags.js"></script>
```

## All Attributes

---
### Hover Attributes

+ `hoverT="text"` change text when hovered
> ```html
> <p hoverT="hovered!">hover me!</p>
> ```

+ `hoverF="color"` change foreground color when hovered
> ```html
> <p hoverF="yellow">hover me!</p>
> ```

+ `hoverB="color"` change background color when hovered
> ```html
> <p hoverB="black">hover me!</p>
> ```

+ `hoverC="fg bg"` change foreground and background color when hovered
> ```html
> <p hoverC="yellow black">hover me!</p>
> ```

+ `hoverA="action"` run action when hovered
> ```html
> <p hoverA="console.log('hovered!')">hover me!</p>
> ```

---

### Click Attributes

+ `clickT="text"`` change text when clicked
> ```html
> <p clickT="clicked!">click me!</p>
> ```

+ `clickF="color"` change foreground color when clicked
> ```html
> <p clickF="yellow">click me!</p>
> ```

+ `clickB="color"` change background color when clicked
> ```html
> <p clickB="black">click me!</p>
> ```

+ `clickC="fg bg"` change foreground and background color when clicked
> ```html
> <p clickC="yellow black">click me!</p>
> ```

+ `clickA="action"` run action when clicked
> ```html
> <p clickA="console.log('clicked!')">click me!</p>
> ```

---

### Abbreviation Attributes

+ `abbr_="a=A; b=B;"` replace **a** to **A** and **b** to **B**, you can add more than two abbreviations
> ```html
> <p abbr_="a=apple; b=banana;">a b cake</p>
> ```

+ `<abbr_ a="A" b="B" c="C">name</abbr_>` a tag to define a **abbr variable** (this tag won't show on the page)
> ```html
> <abbr_ a="apple" b="banana" c="cake">foods</abbr_>
> ```

+ `abbrV="name"` set attr by variable
> ```html
> <p abbrV="food">a b cake</p>
> ```

---

### Font Style Attributes

+ `B` bold text
> ```html
> <p B>BOLD</p>
> ```

+ `I` italic text
> ```html
> <p I>italic</p>
> ```

+ `SC` small caps text
> ```html
> <p SC>Small Caps</p>
> ```

+ `UPPER` uppercase text
> ```html
> <p UPPER>uppercase</p>
> ```

+ `LOWER` lowercase text
> ```html
> <p LOWER>LOWERCASE</p>
> ```

+ `TITLE` capitalize text
> ```html
> <p TITLE>Capitalize</p>
> ```

---

### Text Decoration Attributes

+ `underline` / `underline="color style thickness"` underline text
> ```html
> <p underline>underline</p>
> <p underline="red wavy 5px">5px red wavy underline</p>
> ```

---

### Other Attributes

+ `cursor="cursor"` set cursor
> ```html
> <p cursor="pointer">link</p>
> ```

---
---

- latest update on 2024-01-07
