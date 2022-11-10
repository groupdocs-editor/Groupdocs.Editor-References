---
title: PresentationFormats
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Encapsule tous les formats de présentation. Inclut les formats suivants  Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. En savoir plus sur les formats de présentationicihttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /fr/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Encapsule tous les formats de présentation. Inclut les formats suivants : [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). En savoir plus sur les formats de présentation[ici](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Renvoie une extension (sans point de début) de ce format de présentation en minuscules |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Renvoie un code MIME pour ce format |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Renvoie un nom complet formel de ce format de présentation |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Renvoie une instance de[`PresentationFormats`](../presentationformats)structure, associée à l'extension de nom de fichier spécifiée, ou lève une exception, si l'extension ne peut pas être correctement analysée |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Détermine si cette instance est égale à l'autre instance IDocumentFormat spécifiée |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Détermine si cette instance est égale à l'autre objet spécifié, qui est vraisemblablement de Boxed PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Détermine si cette instance est égale à l'autre instance PresentationFormats spécifiée |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Renvoie un code de hachage, qui est immuable pour cette instance |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Vérifie deux instances PresentationFormats données sur l'égalité |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Vérifie deux instances PresentationFormats données sur l'inégalité |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | Le fichier OpenDocument Presentation (ODP) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | Le fichier de modèle de présentation OpenDocument (OTP) représente les fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Le fichier de modèle de présentation Microsoft PowerPoint 97-2003 (POT) représente les fichiers de modèle Microsoft PowerPoint créés par les versions PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) sont des fichiers prenant en charge les macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou supérieur et contiennent des paramètres par défaut qui peuvent être utilisés pour créer d'autres fichiers de présentation. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Le fichier Microsoft Office Open XML PresentationML Macro-Free Template (POTX) représente les présentations de modèles Microsoft PowerPoint créées avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Les fichiers de diaporama Microsoft PowerPoint 97-2003 (PPS) sont créés à l'aide de Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Les fichiers Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) sont créés avec Microsoft PowerPoint 2007 ou supérieur. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Les fichiers Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX) sont créés à l'aide de Microsoft PowerPoint 2007 et supérieur à des fins de diaporama. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Présentation PowerPoint (.ppt) représente un fichier PowerPoint composé d'une collection de diapositives à afficher sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Présentation Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Fichiers PPTM (Microsoft Office Open XML PresentationML Macro-Enabled Document) créés avec Microsoft PowerPoint 2007 ou des versions supérieures. Ils sont similaires aux fichiers PPTX à la différence que le latéral ne peut pas exécuter de macros bien qu'ils puissent contenir des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) est un fichier de présentation créé avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation XML ouvert de Microsoft PowerPoint. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Renvoie une classe interne, qui fournit des possibilités énumérables sur tous les formats de présentation existants |

## Autres membres

| Nom | La description |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implémente l'interface générique IEnumerable, qui permet une possibilité "foreach" pour le type PresentationFormats |

### Voir également

* interface [IDocumentFormat](../idocumentformat)
* espace de noms [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
