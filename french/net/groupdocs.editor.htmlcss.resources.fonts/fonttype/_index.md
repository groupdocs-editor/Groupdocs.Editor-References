---
title: "FontType"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente un type de police pris en charge"
type: docs
weight: 360
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Représente un type de police pris en charge

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Représente un type de police EOT (Embedded OpenType) |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Représente un type de police OTF (OpenType Font) |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | Représente une police TrueType Collection (TTC) |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Représente un type de police TTF (TrueType Font) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Valeur spéciale, qui indique une ressource de police indéfinie, inconnue ou non prise en charge |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Représente un type de police WOFF (Web Open Font Format) |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Représente un type de police WOFF2 (Web Open Font Format version 2) |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Renvoie le nom compatible CSS de ce type de police, qui est utilisé dans la règle @font-face |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Extension de nom de fichier (sans le caractère point) pour ce type de police |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Format de police pour le format @font-face |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Renvoie un nom officiel de ce type de police |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | Code MIME d'un type de police particulier |

## Méthodes

| Nom | Description |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Renvoie le premier type de police du jeu spécifié, qui n'est pas une valeur "Undefined", ou le type de police "Undefined" sinon (lorsque tous les éléments sont "Undefined") |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Renvoie la valeur FontType, qui est équivalente au nom compatible CSS spécifié du type de police |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Renvoie la valeur FontType, qui est équivalente à l'extension de nom de fichier extraite du nom de fichier spécifié |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Renvoie la valeur FontType, qui est équivalente au code MIME spécifié |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Détermine si cette instance est égale à l'instance "FontType" spécifiée |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non casté spécifié, qui est probablement une autre instance "FontType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Renvoie un code de hachage, qui est un nombre constant pour ce type de valeur spécifique |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Vérifie si deux valeurs "FontType" sont égales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Vérifie si deux valeurs "FontType" ne sont pas égales |

### Voir aussi

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
