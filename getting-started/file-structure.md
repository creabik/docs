---
description: >-
  This section is about the zipkit File structure. You will learn where to find
  the files you need to start working and how to order them. zipkit has many
  files and it's easy to get lost. Let's dive int
---

# File Structure

## Global structure

```d
addkit template
| -- assets
| --- |---- css
| --- |---- fonts
| --- |---- images
| --- |---- js
| -- Home
| -- blog-pages
| -- author-pages
| -- inner-pages
| --- index.html
```

## Sass structure

Addkit relies on a heavy but modular scss structures. You only import in your Style file the partials that you need. This how scss files are organized. Of course, you will never find them all at one in one place. We simply display them here in a friendly manner so you can identify each one of them.

```d
scss 
| -- Bases
| --- |---- _bases.scss
| --- | --- _colors.scss
| -- elements
| --- |---- _Buttons.scss
| --- |---- _inputs.scss
| -- Helpers
| --- |---- _classes.scss
| --- |---- _mixins.scss
| --- |---- _variable.scsss
| -- Layouts
| --- |---- _navbars.scss
| --- |---- _headers.scss
| --- |---- _sections.scss
| --- |---- _footers.scss
| --- |---- _others.scss
| --- Style.scss
```



