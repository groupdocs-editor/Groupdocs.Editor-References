---
title: "PresentationFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Encapsule tous les formats de présentation. Inclut les formats suivants"
type: docs
weight: 120
url: /fr/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Regroupe tous les formats de présentation. Inclut les formats suivants :

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

En savoir plus sur les formats de présentation [ici](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Obtient une collection énumérable de tous les [`PresentationFormats`](../presentationformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Récupère une instance du type spécifié [`PresentationFormats`](../presentationformats) qui possède l’extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Convertit une chaîne représentant une extension de fichier en un objet [`PresentationFormats`](../presentationformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Presentation (PPT). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Présentation Microsoft PowerPoint 95 (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Document Microsoft Office Open XML PresentationML avec macros (PPTM). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Document Microsoft Office Open XML PresentationML sans macros (PPTX). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptx). |

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
