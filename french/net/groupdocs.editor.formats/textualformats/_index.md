---
title: TextualFormats
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Encapsule tous les formats textuels basés sur du texte y compris le balisage XML HTML et autres. Inclut les formats suivants  Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /fr/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Encapsule tous les formats textuels (basés sur du texte), y compris le balisage (XML, HTML) et autres. Inclut les formats suivants : [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Renvoie une extension (sans point de début) de ce format textuel en minuscules |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Renvoie un code MIME pour ce format |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Renvoie un nom complet formel de ce format textuel |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Renvoie une instance de[`TextualFormats`](../textualformats)structure, associée à l'extension de nom de fichier spécifiée, ou lève une exception, si l'extension ne peut pas être correctement analysée |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Détermine si cette instance est égale à l'autre instance IDocumentFormat spécifiée |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Détermine si cette instance est égale à l'autre objet spécifié, qui est vraisemblablement de Boxed TextualFormats |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Détermine si cette instance est égale à l'autre instance TextualFormats spécifiée |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Renvoie un code de hachage, qui est immuable pour cette instance |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Renvoie le nom de ce format particulier, identique à la propriété 'Name' |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Vérifie deux instances TextualFormats données sur l'égalité |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Vérifie deux instances TextualFormats données sur l'inégalité |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help est un format binaire d'aide en ligne propriétaire de Microsoft, composé d'un ensemble de pages HTML, d'un index et d'autres outils de navigation. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Le document HTML (HyperText Markup Language) est l'extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) est un format de fichier standard ouvert pour le partage de données qui utilise du texte lisible par l'homme pour stocker et transmettre des données. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown est un langage de balisage léger permettant de créer du texte formaté à l'aide d'un éditeur de texte brut. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | L'encapsulation MIME de documents HTML agrégés est un format d'archive de page Web utilisé pour combiner, dans un seul fichier informatique, le code HTML et ses ressources d'accompagnement. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) représente un document texte qui contient du texte brut sous forme de lignes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Document XML (eXtensible Markup Language) similaire au HTML mais différent dans l'utilisation de balises pour définir des objets. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Renvoie une classe interne, qui fournit des possibilités énumérables sur tous les formats textuels existants. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implémente l'interface générique IEnumerable, qui permet une possibilité "foreach" pour le type TextualFormats |

### Voir également

* interface [IDocumentFormat](../idocumentformat)
* espace de noms [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
