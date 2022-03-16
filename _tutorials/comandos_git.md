---
layout: single
title: Comandos básicos de Git
excerpt: Tutorial que lista comandos básicos de Git
author_profile: true
#comments: true
categories: 
    - Comandos de Computacao
---

Antes de comecar, atualize os gems da linguagem ruby:

```
    bundle update
```


Caso tenha feito alterações no próprio no site do Github, a versão local estará ultrapassada em relação à versão do site. Então, use o comando "pull" localmente antes de fazer qualquer coisa.

```
    git pull --rebase
```

Comandos básicos para fazer alterações no site.

```
    bundle exec jekyll build
    git add .
    git commit -m "Adiciona o primeiro tutorial."
    git push -u origin main
```



