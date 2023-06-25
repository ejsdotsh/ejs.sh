---
title: "YACHT Another Custom Hugo Theme"
draft: false
# image: //via.placeholder.com/640x150
alt_text: "YACHT Another Custom Hugo Theme"
summary: "YACHT Another Custom Hugo Theme"
status: "active"
tech_used:
  - SCSS
  - HTML
---

***under construction***

after spending a lot of time with other people's themes, i decided that i wanted to learn how to do it, and created my own...but it needed a name. when graduating from highschool, i was voted *"most likely to own a yacht"* by my senior class. i don't think this is what they meant...

***YACHT*** ***A***nother ***C***ustom ***H***ugo ***T***heme

***YACHT*** is a recursively named, mobile-first, accessible, and responsive theme for the [Hugo][1] static site generator, using the [Catppuccin][2] color palette, and styled with [BulmaCSS][3].

***under construction***

## getting your own YACHT

when it's been constructed, the preferred way of getting a **YACHT** for yourself is by using `Hugo modules` in `config.toml`:

```toml
theme = "github.com/ejsdotsh/yacht-hugo-theme"

[module]
  [[module.imports]]
    path = "github.com/ejsdotsh/yacht-hugo-theme"
```

or in `config.yaml`:

```yaml
theme: "github.com/ejsdotsh/yacht-hugo-theme"
module:
  imports:
    path: "github.com/ejsdotsh/yacht-hugo-theme"
    disable: false
```

## references

- Brian P. Hogan's [Build Websites with Hugo](https://pragprog.com/titles/bhhugo/build-websites-with-hugo)
- Atishay Jain's [Hugo in Action](https://www.manning.com/books/hugo-in-action)
- Catppuccin [palette](https://github.com/catppuccin/palette/)

[1]: <https://gohugo.io> "Hugo"
[2]: <https://github.com/catppuccin/catppuccin/blob/main/docs/style-guide.md> "Catppuccin Style Guide"
[3]: <https://bulmaio> "BulmaCSS"
