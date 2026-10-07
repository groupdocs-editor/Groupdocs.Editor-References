---
title: "TextType"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente un type de ressource textuelle pris en charge"
type: docs
weight: 640
url: /fr/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

Représente un type de ressource textuelle pris en charge

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | Type CSS de la ressource textuelle |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | Valeur spéciale qui indique une ressource textuelle indéfinie, inconnue ou non prise en charge |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | Type XML de la ressource textuelle |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | Extension de fichier (sans le caractère point initial) d'une ressource textuelle particulière |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | Renvoie un nom officiel de ce type de ressource textuelle |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | Code MIME d'un type de ressource textuelle particulier |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | Renvoie la valeur TextType, qui est équivalente à l'extension de nom de fichier, extraite du nom de fichier spécifié avec extension ou de l'extension pure |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non converti spécifié, qui est probablement une autre instance "TextType" |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | Détermine si cette instance est égale à l'instance "TextType" spécifiée |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | Renvoie un code de hachage, qui est un nombre constant pour ce type de valeur spécifique |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | Définit si deux instances spécifiques "TextType" sont égales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | Définit si deux instances spécifiques "TextType" ne sont pas égales |

### Voir aussi

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
