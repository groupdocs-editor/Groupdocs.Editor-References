---
title: "EnablePagination"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée false."
type: docs
weight: 30
url: /fr/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### Remarques

En essence, la plupart des formats de livre numérique sont des formats à flux comme Office Open XML, où le contenu est continu et est découpé en chapitres mais pas en pages. Cependant, ils contiennent certaines informations spécifiques aux pages comme les numéros de page, les notes de bas de page, les en-têtes/pieds de page, etc. Certains lecteurs de livres numériques effectuent une division du contenu en pages, tandis que d’autres (en particulier sur mobile) — ne le font pas. Cette option permet de contrôler comment le contenu du livre numérique doit être représenté en HTML/CSS lors de l’édition — en mode flottant (`false`) ou paginé (`true`).

### Voir aussi

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
