# Jekyll Portfolio · Listo para Netlify

Un starter minimalista para publicar proyectos:

- **Colección `projects`** con páginas individuales.
- **Filtro por etiquetas** + búsqueda rápida sin librerías.
- **SEO** con `jekyll-seo-tag` y **sitemap** automático.
- **Diseño oscuro** moderno, sin frameworks.
- **Preparado para Netlify** con `netlify.toml`.

## Desarrollo local

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

## Despliegue en Netlify
1. Sube este repo a GitHub/GitLab/Bitbucket.
2. En Netlify, **Add new site > Import an existing project**.
3. Build command: `bundle exec jekyll build`
4. Publish directory: `_site`

## Añadir proyectos
Crea archivos en `_projects/mi-proyecto.md` con front matter:

```yaml
---
title: "Mi Proyecto"
description: "Resumen corto"
tags: ["web","datos"]
year: 2025
cover: /assets/img/mi-proyecto.jpg
demo: https://mi-demo.com
repo: https://github.com/yo/mi-proyecto
date: 2025-09-01
---

Texto en Markdown con detalles, imágenes, etc.
```
