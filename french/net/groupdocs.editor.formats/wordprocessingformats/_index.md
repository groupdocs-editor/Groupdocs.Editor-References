---
title: WordProcessingFormats
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Encapsule tous les formats de traitement de texte. Inclut les types de fichiers suivants  Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . En savoir plus sur les formats de traitement de texteicihttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /fr/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Encapsule tous les formats de traitement de texte. Inclut les types de fichiers suivants : [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . En savoir plus sur les formats de traitement de texte[ici](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Renvoie une extension (sans point de début) de ce format WordProcessing en minuscules |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Renvoie un code MIME pour ce format |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Renvoie un nom complet formel de ce format WordProcessing |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Renvoie une instance de[`WordProcessingFormats`](../wordprocessingformats)structure, associée à l'extension de nom de fichier spécifiée, ou lève une exception, si l'extension ne peut pas être correctement analysée |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Détermine si cette instance est égale à l'autre instance IDocumentFormat spécifiée |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Détermine si cette instance est égale à l'autre objet spécifié, qui est vraisemblablement de WordProcessingFormats en boîte |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Détermine si cette instance est égale à l'autre instance WordProcessingFormats spécifiée |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Renvoie un code de hachage, qui est immuable pour cette instance |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Renvoie le nom de ce format particulier, identique à la propriété 'Name' |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Vérifie deux instances WordProcessingFormats données sur l'égalité |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Renvoie une valeur d'octet du champ sous-jacent de l'instance WordProcessingFormats spécifiée (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Vérifie deux instances WordProcessingFormats données sur l'inégalité |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) représente les documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Les fichiers Office Open XML WordProcessingML Macro-Enabled Document (DOCM) sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la possibilité d'exécuter des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée de binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Template sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres pré-formatés pour la génération d'autres fichiers DOC ou DOCX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) représente un fichier de modèle créé avec Microsoft Word 2007 ou une version ultérieure. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres préformatés pour la génération d'autres fichiers DOCX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d'un package ZIP |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Les fichiers Open Document Format Text Document (ODT) sont des types de documents créés avec des applications de traitement de texte basées sur le format OpenDocument Text File. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) représente les modèles de documents générés par les applications conformément au format standard OpenDocument d'OASIS. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) représente une méthode d'encodage de texte formaté et de graphiques à utiliser dans les applications. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Format XML de Microsoft Office Word 2003 — WordProcessingML ou WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Renvoie une classe interne, qui fournit des possibilités énumérables sur tous les formats de traitement de texte existants |

## Autres membres

| Nom | La description |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Implémente l'interface générique IEnumerable, qui permet une possibilité "foreach" pour le type WordProcessingFormats |

### Remarques

Les codes MIME sont extraits des ressources indiquées : https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Voir également

* interface [IDocumentFormat](../idocumentformat)
* espace de noms [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
