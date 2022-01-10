---
title: "How to Translate Site Data"
date: 2020-06-07T06:20:50+06:00
menu:
  sidebar:
    name: Translating Homepage
    identifier: translation-homepage
    parent: translation
    weight: 510
---

The default "Hello, I am John" text plus the typewritten text lives in `data/author.yaml`. Change the file to reflect the changes you need.

To have multiple translations of this information, create one directory or folder per language configured in `config.yaml`, e. g. `en`, `fr`, `ar`.

Example part from config.yaml:
```
languages:
  ar:
    languageName: Arabic
    weight: 1
  en:
    languageName: English
    weight: 2
  fr:
    languageName: French
    weight: 3
```

In each of these directories create one `author.yaml` file.

Altogether, the structure in `data` should look like that:
```
data/
  ar/
    author.yaml
  en/
    author.yaml
  fr/
    author.yaml
```
