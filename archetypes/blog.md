---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: []
summary: "Una frase. Sale en el listado y en el RSS; si no la pones, Hugo recorta las primeras palabras y queda peor."
---

Texto en markdown. Pon `draft: false` cuando esté lista.
