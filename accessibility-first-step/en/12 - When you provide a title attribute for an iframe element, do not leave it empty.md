---
id:         12
priority:   Error
topic:      HTML
selector:   iframe[title]
status:     not started
---

# When you provide a title attribute for an iframe element, do not leave it empty

## Purpose

Permettre la restitution d'un contenu décrivant la fonction et/ou le contenu de l'élément.

## Technical solution

Ajouter un contenu à l'attribut `title` des éléments `<iframe>`.

## Control method

Inspecter le code afin de vérifier la présence de contenu sur les attributs `title` des éléments `<iframe>`.

