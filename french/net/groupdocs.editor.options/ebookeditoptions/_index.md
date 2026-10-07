---
title: "EbookEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier et d'ajuster des options personnalisées pour l'édition de documents Ebook dans tous les formats pris en charge ePub, MOBI et AZW3."
type: docs
weight: 830
url: /fr/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

Permet de spécifier et d’ajuster des options personnalisées pour l’édition de documents de livre électronique dans tous les formats pris en charge : ePub, MOBI et AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | Initialise une nouvelle instance de la classe [`EbookEditOptions`](../ebookeditoptions), où toutes les options sont définies à leurs valeurs par défaut |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | Initialise une nouvelle instance de la classe [`EbookEditOptions`](../ebookeditoptions) avec le mode de pagination spécifié |

## Propriétés

| Nom | Description |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | Spécifie si les informations de langue sont exportées vers le balisage HTML sous forme d'attributs HTML 'lang'. Cette option peut être utile pour la conversion aller-retour des documents multilingues. Par défaut, elle est désactivée (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (`false`). |

### Remarques

Formats d'e-book pris en charge :

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Publication électronique)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
