---
title: "TextualFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Encapsule tous les formats textuels basés sur du texte, y compris le balisage XML HTML et autres. Inclut les formats suivants Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /fr/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Encapsule tous les formats textuels (basés sur du texte), y compris le balisage (XML, HTML) et autres. Inclut les formats suivants : [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Obtient une collection énumérable de tous les [`TextualFormats`](../textualformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Récupère une instance du type spécifié [`TextualFormats`](../textualformats) qui possède l'extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Convertit une chaîne représentant une extension de fichier en objet [`TextualFormats`](../textualformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help est un format binaire d'aide en ligne propriétaire de Microsoft, composé d'une collection de pages HTML, d'un index et d'autres outils de navigation. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Le document HyperText Markup Language (HTML) est l'extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) est un format de fichier standard ouvert pour le partage de données qui utilise du texte lisible par l'homme pour stocker et transmettre les données. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown est un langage de balisage léger pour créer du texte formaté à l'aide d'un éditeur en texte brut. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | L'encapsulation MIME de documents HTML agrégés est un format d'archive de pages Web utilisé pour combiner, dans un seul fichier informatique, le code HTML et ses ressources associées. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Le document texte brut (TXT) représente un document texte contenant du texte brut sous forme de lignes. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Document eXtensible Markup Language (XML) qui est similaire à HTML mais différent dans l'utilisation des balises pour définir des objets. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/web/xml). |

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
