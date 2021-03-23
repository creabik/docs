---
description: 'Follow the steps below to setup your site template:'
---

# Instalation

## **Downloading the Template**

Once you have downloaded the zip file from Themeforest, unzip it using your standard zip software. When it has finished you should have a folder with the following files & directories inside.

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

{% hint style="info" %}
1. Connect to your website host, using some of many FTP clients, for example FileZilla.
2. After opened the template folder you will need to upload any niche template you need, for example if you need to upload \(**home1 - services**\) template, just go to the pages folder then remove all other pages  and upload all content or specific HTML files as per your need to your website server folder.
{% endhint %}



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



