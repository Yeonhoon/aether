---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
description: ""
categories: []
toc: true
dropCap: true
displayInMenu: false
displayInList: true
draft: false
resources:
- name: featuredImage
  src: ""
  params:
    description: ""
---

output:
  html_document:
    fig_height: 5
    fig_width: 10
    highlight: textmate
    theme: cosmo
    toc: yes
    toc_depth: 3
    toc_float: yes

---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo=F, fig.align = "center", message=F, warning=F, fig.height = 5, fig.widget = 5, cache=T, dpi = 300)
```
