---
title: FixedLayoutFormats
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Encapsule tous les formats à mise en page fixe également appelés pages fixes y compris PDF et XPS cela ninclut pas les images raster
type: docs
weight: 80
url: /fr/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Encapsule tous les formats à mise en page fixe (également appelés "pages fixes"), y compris PDF et XPS (cela n'inclut pas les images raster)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Renvoie une extension (sans point de début) de ce format de mise en page fixe en minuscules |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Renvoie un code MIME pour ce format |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Renvoie un nom complet formel de ce format de mise en page fixe |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Renvoie une instance de[`FixedLayoutFormats`](../fixedlayoutformats)structure, associée à l'extension de nom de fichier spécifiée, ou lève une exception, si l'extension ne peut pas être correctement analysée |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Détermine si cette instance est égale à l'autre instance FixedLayoutFormats spécifiée |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Détermine si cette instance est égale à l'autre instance IDocumentFormat spécifiée |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Détermine si cette instance est égale à l'autre objet spécifié, qui est vraisemblablement de Boxed FixedLayoutFormats |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Renvoie un code de hachage, qui est immuable pour cette instance |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Renvoie le nom de ce format particulier, identique à la propriété 'Name' |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Vérifie deux instances FixedLayoutFormats données sur l'égalité |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Renvoie une valeur d'octet du champ sous-jacent de l'instance FixedLayoutFormats spécifiée (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Vérifie deux instances FixedLayoutFormats données sur l'inégalité |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et autres documents de référence dans un format indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | Le fichier XPS représente les fichiers de mise en page basés sur les spécifications papier XML créées par Microsoft. Il a été développé pour remplacer le format de fichier EMF et est similaire au format de fichier PDF, mais utilise XML dans la mise en page, l'apparence et les informations d'impression d'un document. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Renvoie une classe interne, qui fournit des possibilités énumérables sur tous les formats de mise en page fixes existants |

## Autres membres

| Nom | La description |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Implémente l'interface générique IEnumerable, qui permet une possibilité "foreach" pour le type FixedLayoutFormats |

### Remarques

Diverses applications de visualisation ou de publication de documents permettent aux utilisateurs d'ouvrir (Adobe Acrobat, XPS Viewer) et parfois de modifier (Adobe InDesign) des documents de formats spécifiques. Ces applications produisent typiquement des documents au format dit "page fixe". Un tel format de document décrit précisément où le contenu d'un document est placé sur chaque page. En interne, le format PDF ou XPS contient une description de chaque page, ainsi que des instructions de dessin, spécifiant la disposition du contenu sur la page. Ceci est similaire aux formats d'image, décrivant où le contenu est affiché sous forme raster ou vectorielle.

### Voir également

* interface [IDocumentFormat](../idocumentformat)
* espace de noms [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
