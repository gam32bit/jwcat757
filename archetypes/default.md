---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
cover:
    image: "{{ .Params.cover.image }}"
    alt: "{{ .Params.cover.alt }}"
    caption: "{{ .Params.cover.caption }}"
---

