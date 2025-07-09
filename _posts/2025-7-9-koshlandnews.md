---
title: "We have news: NEWS!"
---

Today, Koshland made its first official online news service called Koshland News.

It is powered by Jekyll and Github pages.

This is the file for the layout.
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>{{ page.title }} - {{ site.title }}</title>
<link rel="stylesheet" href="{{ '/assets/dark.css' | relative_url }}">
</head>
<body>
  <header>
   <h1><a href="{{ '/' | relative_url }}">{{ site.title }}</a></h1>
    <p><em>{{ site.description }}</em></p>
    <hr>
  </header>

  {{ content }}

  <hr>
  <footer>
    <p>&copy; {{ site.time | date: "%Y" }} {{ site.title }}</p>
  </footer>
</body>
</html
```