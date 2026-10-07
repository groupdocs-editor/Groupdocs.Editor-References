---
title: "EbookSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement du document dans tous les formats eBook pris en charge : ePub, MOBI et AZW3."
type: docs
weight: 840
url: /fr/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer le document dans tous les formats de livre électronique pris en charge : ePub, MOBI et AZW3.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | Ce constructeur sans paramètre crée une nouvelle instance de EbookSaveOptions avec le format de sortie ePub (pouvant ensuite être modifié via la propriété [`OutputFormat`](./outputformat)). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | Crée une nouvelle instance de [`EbookSaveOptions`](../ebooksaveoptions) avec le format de sortie e-Book obligatoire spécifié, tandis que tous les autres paramètres sont par défaut |

## Propriétés

| Nom | Description |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant. La valeur par défaut est `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | Spécifie le format du fichier e-Book résultant : IDPF ePub, MOBI ou AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | Spécifie le niveau maximal de titres auquel diviser le fichier e-Book. La valeur par défaut est `2`. Le définir à `0` désactivera la division, de sorte que tout le contenu de l'e-Book sera incorporé dans un seul paquet à l'intérieur du fichier résultant. |

### Remarques

Formats d'e-book pris en charge :

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Publication électronique)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
